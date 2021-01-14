<template>
  <div class="flex w-screen h-screen">
    <!-- <router-view/> -->
    <div class="h-screen border w-20">
      <side-bar />
    </div>
    <div class="h-screen w-full p-5">
      <div class="ml-10 w-11/12">
        <situation-board />  
      </div>
      <br>
      <div class="ml-10 w-11/12 h-4/6">
        <login-page></login-page>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';
    import  SideBar  from '@/components/sideBar/SideBar.vue';
    import  SituationBoard  from '@/components/situationBoard/SituationBoard.vue';
    import  LoginPage  from '@/components/RouteComponent/LoginPage.vue';

    @Component({
      components: {
        SideBar, SituationBoard, LoginPage
      }
    })
    export default class App extends Vue {
        
    }

</script>

<style lang="scss">

// @import '@/style/index';
</style>
