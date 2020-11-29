<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
/* royal blue - #5166DD
   whisper - #F1EEF6
   Carey's pink - #CBA2B0
 */
 * {
   font-family: 'Raleway', sans-serif;
 }
:root{
  --royal-blue: #5166DD;
  --whisper: #F1EEF6;
  --pink: #fcaea2;
  --deep: #2E2C5E;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
.full-height{
  min-height: 85vh;
}
.hero-height {
  min-height: 70vh;
}
.nav-height{
  min-height: 15vh;
}
.primary-bg{
  background-color: var(--royal-blue);
}
.secondary-bg{
  background-color: var(--whisper);
}
.alt-bg {
  background-color: var(--pink);
}
.alt-color {
  color: var(--pink);
}
.primary-color {
  color: var(--royal-blue);
}
.secondary-color {
  color: var(--whisper);
}
</style>
