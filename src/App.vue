<template>
<div class = "menu">
  <a>menu</a>
</div>
</template>

<script>

export default {
  name: 'App',data(){
    return {
      temporature : 23, region : 'gangnam', dust : 30


    }
  },
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
.menu {
  background : darkslateblue;
  padding : 15px;
  border-radius: 5px;
}

.menu a {
  color : white;
  padding : 10px;
}
</style>
