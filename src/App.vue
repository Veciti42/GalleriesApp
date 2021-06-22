<template>
  <div id="app">

  </div>
</template>

<script>
import Galleries from '.components/Galleries';

export default {
  name: 'App',
  components: {
    Galleries
  },
  data() {
    return {
      galleries: [
        {
          id: 1,
          title: 'Abstrakti'
        },
        {
          id: 2,
          title: 'Modernizam'
        }
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
