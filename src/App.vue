<template>
  <div id="app">
    <div class="wrapper">
    <Index />
    </div>
  </div>
</template>

<script>

import Index from './index.vue'

export default {
  name: 'App',
  components: {
    
    Index
  }
}
</script>

<style>

body #app {
    display: flex;
    flex-direction: column;
    width: 100%;
    min-height: 100vh;
}
body .wrapper {
    display: flex;
    flex: 1 1 auto;
}
body .wrapper > * {
    width: 100%;
}

</style>
