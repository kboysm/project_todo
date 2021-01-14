<template>
  <div class="flex w-screen h-screen">
    <!-- <router-view/> -->
    <div class="h-screen border w-20">
      <side-bar />
    </div>
    <div class="h-screen w-full p-12">
      <div class="w-4/5 h-96">
        <situation-board />  
      </div>
      <div class="bg-gray-100">
        main
      </div>
    </div>
  </div>
</template>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';
    import  SideBar  from '@/components/sideBar/SideBar.vue';
    import  SituationBoard  from '@/components/situationBoard/SituationBoard.vue';

    @Component({
      components: {
        SideBar, SituationBoard
      }
    })
    export default class App extends Vue {
        
    }

</script>

<style lang="scss">

// @import '@/style/index';
</style>
