<template>
  <div>
    <!-- <router-view/> -->
    <side-bar />
  <situation-board />
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
@import '@/style/index';
</style>
