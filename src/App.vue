<template>
    <div id="app">
        <nav/> 
        <router-view />
    </div>
</template>
<script> 
import Nav from './components/Shared/Nav.vue'
export default{
  name: "App",
  components: { Nav }
}
</script>
<style lang="scss">
</style>
