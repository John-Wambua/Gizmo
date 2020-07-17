<template>
  <div>

    <TheHeader @sidenavToggle="displaySideNav=!displaySideNav"/>
    <TheSidenav
      :show="displaySideNav"
    @close="displaySideNav=false"/>
    <Nuxt />
  </div>
</template>

<style>
html{
  font-family: 'Open Sans','sans-serif';
}
  body{
    margin: 0;
  }

</style>
<script>
  import TheHeader from "../components/Navigation/TheHeader";
  import TheSidenav from "../components/Navigation/TheSidenav";
  export default {
    components: {TheSidenav, TheHeader},
    data(){
      return{
        displaySideNav:false
      }
    }
  }
</script>
