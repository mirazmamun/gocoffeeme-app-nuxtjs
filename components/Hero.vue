<template>
  <section class="hero-container">
    <!-- CONTENT -->
    <div class="text-container">
      <h1 class="title">{{ title }} {{ test }}</h1>
      <h2 class="subtitle">{{ subtitle }}</h2>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.hero-container {
  height: 100vh;
  background-image: url('../assets/images/hero_1920.jpg');
  background-size: cover;
  .text-container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    .title {
      font-family: 'Quicksand', 'Source Sans Pro', -apple-system,
        BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial,
        sans-serif;
      width: 100%;
      font-weight: 300;
      font-size: 100px;
      color: white;
      letter-spacing: 1px;
    }

    .subtitle {
      width: 100%;
      font-weight: 300;
      font-size: 42px;
      color: white;
      word-spacing: 5px;
      display: block;
      padding-bottom: 15px;
    }
  }

  .links {
    padding-top: 15px;
  }
}
</style>
<script>
import { mapMutations } from 'vuex'
export default {
  data() {
    //do the translation
    return {
      title: 'GoCoffeeMe',
      subtitle: 'Reward your mate with coffee'
    }
  },
  components: {},
  computed: {
    test () {
      console.log(this.$store.state.dashboard);
      return this.$store.state.dashboard.test;
    }
  }
}
</script>

