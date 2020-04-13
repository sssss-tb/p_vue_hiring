<template>
  <div class="container">
    <h1 class="title">{{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: "PaymentReviewAnnual",
  props: {
    title: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  display: block;
  padding-left: 60px;
}
.container .title {
  text-align: left;
}
</style>
