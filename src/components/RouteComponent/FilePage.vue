<template>
    <div class="h-full">
        <div class="shadow-md ">
        <img class="inline-block" src="../../assets/Icon/prepend.svg" alt="">
        <input type="text"
        id="searchBar"
        placeholder=" "
        class="border-b-2 w-11/12 h-full inline-block focus:outline-none focus:ring focus:border-blue-300" />
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