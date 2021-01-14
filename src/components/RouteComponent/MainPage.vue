<template>
    <div class="h-full shadow-xl flex items-center justify-center p-12">
        <div class="w-full border rounded">
            
            <div class="flex h-16 pl-12 pr-12"> <!-- top -->
                <img class="inline-block flex-none w-18 h-18" src="@/assets/Icon/left.svg" alt="">
                <div  class="inline-block flex-grow text-center flex justify-center items-center">
                    cal-2020
                </div>
                <img class="inline-block flex-none w-18 h-18" src="@/assets/Icon/right.svg" alt="">
            </div>
            <hr>
            <div class="grid grid-cols-8">
                <div class="flex justify-center items-center w-full h-16">Wk</div>
                <div class="flex justify-center items-center w-full h-16">Su</div>
                <div class="flex justify-center items-center w-full h-16">Mo</div>
                <div class="flex justify-center items-center w-full h-16">Tu</div>
                <div class="flex justify-center items-center w-full h-16">We</div>
                <div class="flex justify-center items-center w-full h-16">Th</div>
                <div class="flex justify-center items-center w-full h-16">Fr</div>
                <div class="flex justify-center items-center w-full h-16">Sa</div>
                <div class="flex justify-center items-center w-full h-16" v-for="item in 30" :key="item">
                    <div class="flex justify-center items-center rounded-full py-3 px-6 bg-gray-400" v-if=" item == 11">
                        {{item}}
                    </div>
                    <div class="flex justify-center items-center rounded-full py-3 px-6 bg-gray-200" v-else-if=" item == 12">
                        {{item}}
                    </div>
                    <div class="flex justify-center items-center rounded-full py-3 px-6 bg-blue-400 text-white" v-else-if=" item == 13">
                        {{item}}
                    </div>
                    <div v-else>
                        {{item}}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import { Component, Vue } from 'vue-property-decorator';

    @Component
    export default class MainPage extends Vue {
        
    }
</script>

<style lang="scss" scoped>
    #searchBar {
        border-bottom: 1px solid black;
    }
</style>