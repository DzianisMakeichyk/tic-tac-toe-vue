<template>
  <div id="app">
    <div id="details">
      <h1>
        Tic Tac Toe
      </h1>
    </div>
    <grid></grid>
  </div>
</template>

<script>
import grid from './components/Grid'

export default {
  name: 'app',
  data () {
      return {
          matches: 0,
          wins: {
              O: 0,
              X: 0
          }
      }
  },
  components: {
      grid
  }
}
</script>

<style>
</style>
