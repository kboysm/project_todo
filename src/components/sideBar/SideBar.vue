<template>
<div class="sideContainer">
    <div class="sideBar">
        <button>
            <img src="../../assets/Icon/face_unlock_24px.svg" alt="user">
        </button>
        <button>
            <img src="../../assets/Icon/event_available_24px.svg" alt="user">
        </button>
        <button>
            <img src="../../assets/Icon/folder_24px.svg" alt="user">
        </button>
        <button>
            <img src="../../assets/Icon/Group.svg" alt="user">
        </button>
        <button>
            <img src="../../assets/Icon/logout.svg" alt="user">
        </button>
        
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