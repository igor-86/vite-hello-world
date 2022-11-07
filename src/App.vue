<script>
import AppTitle from "./components/AppTitle.vue";

export default {
  data() {
    return {
      message: "ciao melinda"
    }
  },
  components: {
    AppTitle,
  },
  methods: {

  }
}

</script>

<template>
  <h1>{{ message }}</h1>
  <section>
    <AppTitle />
  </section>
</template>

<style>

</style>
