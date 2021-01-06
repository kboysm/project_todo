<template>
    <div class = "situationContainer">
        <div class= "situationBoard">
            <div class= "textArea">
                <span class= "fieldName">field name,</span>
                <span class= "myName">lim sang min</span>
                <br>
                <span class= "textHomePage">
                    HomePage
                </span>
            </div>
            <div class= "imgArea">
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