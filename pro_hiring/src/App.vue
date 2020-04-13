<template>
  <div id="app">
    <PremiumPurchasing title="Premium Package" />
  </div>
</template>

<script>
import PremiumPurchasing from "./components/PremiumPurchasing.vue";

export default {
  name: "App",
  components: {
    PremiumPurchasing
  }
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
