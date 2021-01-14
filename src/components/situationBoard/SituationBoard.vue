<template>
    <div class="flex items-center border bg-blue-400 rounded-2xl">
        <div class= "flex w-full h-full p-10">
            <div class="text-5xl bold w-5/6 " style="line-height:80%">
            <div class="ml-12 mt-5">
                <span class= "fieldName">field name,</span>
                <span class= "text-white">lim sang min</span>
                <br><br>
                <span class= "textHomePage">
                    HomePage
                </span>
            </div>
            </div>
            <div class="w-1/6">
                <img class= "mainImg" src="../../assets/mainImg.svg" alt="mainImg">
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';

    @Component
    export default class SituationBoard extends Vue {
        
    }
</script>

<style scoped>

</style>