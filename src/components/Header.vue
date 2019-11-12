<template>
  <div id="nav">
    <router-link to="/">Home</router-link>|
    <router-link to="/about">About</router-link>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
};
</script>


<style scoped>
#nav {
}

#nav a {
  font-weight: bold;
  text-decoration: none;
  color: #666;
}
#nav a:hover {
  color: #2c3e50;
}
#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
