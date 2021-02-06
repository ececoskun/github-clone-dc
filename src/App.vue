<template>
    <div id="app">
        <nav/> 
        <router-view />
    </div>
</template>
<script> 
import Nav from './components/Shared/Nav.vue'
export default{
  components: { Nav },
    name: "App"
}
</script>
<style lang="scss">
</style>
