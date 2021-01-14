<template>
    <div class="static h-full">
        <div class="shadow-md ">
        <img class="inline-block" src="@/assets/Icon/prepend.svg" alt="">
        <input type="text"
        id="searchBar"
        placeholder=" "
        class="border-b-2 w-11/12 h-full inline-block focus:outline-none" />
        </div>
        <div class="flex flex-row-reverse pr-12 pt-3">
            <img class="inline-block" src="@/assets/Icon/plusBtn.svg" alt="">
        </div>
        <div class="grid grid-cols-4 gap-4 pl-12 ml-12">
            <div class="flex justify-center item-center w-64 h-40 bg-gray-200 rounded-lg"
            v-for="( item , index ) in 12" :key="index"
            >
                <img src="@/assets/Icon/lock.svg" alt="">
            </div>
        </div>
    </div>
</template>

<script>
    import { Component, Vue } from 'vue-property-decorator';

    @Component
    export default class FilePage extends Vue {
        
    }
</script>

<style lang="scss" scoped>
    #searchBar {
        border-bottom: 1px solid black;
    }
</style>