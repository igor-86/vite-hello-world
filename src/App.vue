<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {
      message: "ciao melinda"
    }
  },
  components: {
    AppTitle,
    AppHero
  },
  methods: {

  }
}

</script>

<template>
  <h1>{{ message }}</h1>
  <section>
    <AppTitle />
    <AppHero />
  </section>
</template>

<style>

</style>
