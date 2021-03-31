<template>
  <side-bar></side-bar>
  <router-view/>
</template>

<style>

</style>
<script>
import SideBar from "./components/SideBar";
export default {
  components: {SideBar}
}
</script>