<template>
  <div id="app">
    <Hello :name="name" />
    <input type="text" v-model="name" placeholder="Enter your name" />
    <div>
      <img alt="Vue logo" src="./assets/doggo.jpeg" />
    </div>
  </div>
</template>

<script>
import Hello from "./components/Hello.vue";

export default {
  name: "App",
  components: {
    Hello,
  },
  data() {
    return {
      name: "",
    };
  },
};
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

input {
  margin-bottom: 20px;
}
</style>
