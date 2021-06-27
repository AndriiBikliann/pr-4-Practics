<template>
  <div id="app">
    <label-comp/>
  </div>
</template>

<script>

import LabelComp from './components/LabelComp.vue'

export default {
  name: 'App',
  components: {
    LabelComp
  },
    data() {
    return {
      
    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(112, 105, 105);
}
</style>
