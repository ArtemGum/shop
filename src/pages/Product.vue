<template>
  <div class="wrapper-content wrapper-content--fixed">
    <section>
      <div class="container">
        <h1></h1>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  created() {
    // console.log({ route: this.$route, id: this.$route.params.id });
    let id = this.$route.params.id;
    let product = this.getters.getProduct(id);
    console.log(product);
  }
};
</script>
