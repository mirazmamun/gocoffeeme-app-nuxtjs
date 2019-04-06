<template>
  <div>
    <!-- Full width contents -->
    <Navbar></Navbar>
    <Hero/>
    <section>
      <Steps/>
    </section>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar'
import Hero from '~/components/Hero'
import Steps from '~/components/Steps'
export default {
  asyncData() {
    //get the translations
    return {}
  },
  fetch() {
    return {}
  },
  components: {
    Navbar,
    Hero,
    Steps
  }
}
</script>

<style>
</style>
