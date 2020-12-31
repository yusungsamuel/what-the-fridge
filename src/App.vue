<template>
  <div id="app">
    <Jumbotron/>
  </div>
</template>

<script>

import Jumbotron from "./components/Jumbotron"
export default {
  name: 'App',
  components: {
    Jumbotron,

  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@700&display=swap');
  *{
    font-family: 'Quicksand', sans-serif;
  }
</style>
