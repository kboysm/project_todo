<template>
<div class="flex flex-col items-center bg-blue-400 h-screen">
    <div class="h-8"></div>
    <div class="h-40">
        <div class="border items-center rounded-full">
            <button class="mt-1 transform hover:rotate-45">
                <img src="../../assets/Icon/face_unlock_24px.svg" alt="user">
            </button>
        </div>
    </div>
    <div class="h-40">
        <div class="border items-center rounded-full">
            <button class="mt-1 transform hover:rotate-45">
                <img src="../../assets/Icon/event_available_24px.svg" alt="user">
            </button>
        </div>
    </div>
    <div class="h-40">
        <div class="border items-center rounded-full">
            <button class="mt-1 transform hover:rotate-45">
                <img src="../../assets/Icon/folder_24px.svg" alt="user">
            </button>
        </div>
    </div>
    <div class="h-40">
    </div>
    <div class="h-40 flex flex-col justify-between">
        <div class="border items-center rounded-full">
            <button class="order-first mt-1 transform hover:rotate-45">
                <img src="../../assets/Icon/Group.svg" alt="user">
            </button>
        </div>
        <div class="border items-center rounded-full">
            <button class="order-last mt-1 transform hover:rotate-45">
                <img src="../../assets/Icon/logout.svg" alt="user">
            </button>
        </div>
    </div>

    </div>
</template>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';

    @Component
    export default class SideBar extends Vue {
        
    }
</script>

<style scoped>

</style>