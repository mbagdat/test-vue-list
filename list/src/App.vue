<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <AppHeader msg="The list of posts" />
    <PostsList />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import PostsList from "./components/PostsList.vue";

export default {
  name: "app",
  components: {
    AppHeader,
    PostsList
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
