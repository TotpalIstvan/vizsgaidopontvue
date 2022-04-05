<template>
  <div id="app">
    <nav>
    <a href="">kártyák</a>
    <a href="">képek</a>
    </nav>
    <form>
      <input type="text"><br>
      <input type="text"><br>
      <input type="datetime"><br>
      <button>Új kártya</button>
    </form>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {
    
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
