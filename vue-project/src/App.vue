<template>
<div id="app">
  <user-profile />
</div>
</template>


<script>
import UserProfile from "./components/UserProfile.vue";

export default {
    name: 'App',
    components: {
        UserProfile
    },
 
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  display: block;
}
</style>
