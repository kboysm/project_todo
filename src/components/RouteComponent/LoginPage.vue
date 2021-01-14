<template>
    <div class="flex justify-center w-full h-full bg-blue-400 rounded-2xl p-12">
        <div class="h-full w-96 bg-geay-500">
            <div class="mt-12 text-4xl font-extrabold text-center">
                Log In
            </div>
            <form action="#" class="mt-5">
                <t-input class="bg-white rounded-full h-14" value=" Email" name="my-input" />
                <br>
                <t-input class="bg-white rounded-full h-14" value=" Password" name="my-input" />
                <br>
                <div>
                    <button class="bg-black text-white w-full h-14 rounded-full">LOG IN</button>
                    <br>
                    <div style="line-height:50%;">
                        <br>
                    </div>
                    <button class="bg-gray-100 w-full h-14 rounded-full">Sign Up</button>
                    <br>
                    <div style="line-height:50%;">
                        <br>
                    </div>
                    <div class="text-center">
                        <a href="#">
                        Forgot Password?
                        </a>
                    </div>
                </div>
            </form>
        </div>
    </div>
</template>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';

    @Component
    export default class LoginPage extends Vue {
        
    }
</script>

<style scoped>

</style>