<template>
  <ChildGreeting fistName="john" />
  <ChildGreeting fistName="jane" />
  <ChildGreeting fistName="jack" />
  <ChildGreeting fistName="dave" />
</template>

<script>
import ChildGreeting from "./components/ChildGreeting.vue";

export default {
  name: "App",
  components: {
    ChildGreeting,
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
</style>
