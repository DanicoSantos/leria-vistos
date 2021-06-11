<template>
  <div class="home">
    <section class="hero is-medium is-info">
      <div class="hero-body">
        <p class="title">
          Hero title
        </p>
        <p class="subtitle">
          Hero subtitle
        </p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
  mounted() {
    this.changePageTitle();
  },
  methods: {
    changePageTitle() {
      document.title = "Home | Leria Vistos";
    },
  },
};
</script>

<style lang="scss"></style>
