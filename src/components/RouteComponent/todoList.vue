<template>
    <div class="flex h-full">
        <div class="w-1/2 flex justify-center items-center">
            <div class="bg-gray-300 h-96 w-10/12 rounded-lg">
                <div class="pl-4 pt-2 h-1/5 text-3xl font-black">
                    complete
                    <hr class="mt-2">
                </div>
                    <div class="h-4/5">
                        <div class="flex flex-row-reverse h-1/4 pr-10" v-for="item in 4" :key="item">
                            <div class="inline-block text-2xl font-black">
                                <span class="line-through pr-10 mb-5">list</span>
                                <button>
                                    <img src="@/assets/Icon/removeBtn.svg" alt="remove">
                                </button>
                            </div>
                        </div>
                    </div>
            </div>
        </div>
        <div class="w-1/2 flex justify-center items-center">
            <div class="bg-gray-300 h-96 w-10/12 rounded-lg">
                <div class="flex pl-4 pt-2 h-1/8 text-3xl font-black">
                    <div class="flex-none inline-block">
                        yet
                    </div>
                    <div class="flex-grow"></div>
                    <div class="flex-none inline-block pr-10">
                        <button>
                            <img src="@/assets/Icon/plusBtn.svg" alt="remove">
                        </button>
                    </div>
                </div>
                    <hr class="mt-2">
                    <div class="h-4/5 mt-6">
                        <div class="flex flex-row-reverse h-1/4 pr-10" v-for="item in 4" :key="item">
                            <div class="inline-block text-2xl font-black">
                                <span class="pr-10">list</span>
                                <button>
                                    <img src="@/assets/Icon/removeBtn.svg" alt="remove">
                                </button>
                            </div>
                        </div>
                    </div>
            </div>
        </div>
    </div>
</template>

<script>
    import { Component, Vue } from 'vue-property-decorator';

    @Component
    export default class todoList extends Vue {
        
    }
</script>

<style lang="scss" scoped>
    #searchBar {
        border-bottom: 1px solid black;
    }
</style>