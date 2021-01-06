<template>
  <div id="app">
    <!-- <router-view/> -->
    <side-bar />

  </div>
</template>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';
    import  SideBar  from '@/components/sideBar/SideBar.vue'

    @Component({
      components: {
        SideBar
      }
    })
    export default class App extends Vue {
        
    }

</script>

<style lang="scss">
@import '@/style/index';

</style>
