<template>
<!--   <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>-->
  <router-view />

  <h1>header 1 </h1>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      title: "weekendview",
    }
  },
  methods: {
    handleClick() {
      console.log(this.$data.title)
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
  color: #2c3e50;
  margin-top: 60px;
}
</style>
