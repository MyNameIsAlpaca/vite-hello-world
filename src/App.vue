
<script>

import AppTitle from "./components/AppTitle.vue"

import AppHero from "./components/AppHero.vue"

export default {
  data() {
    return {
    };
  },
  components: {
    AppTitle,
    AppHero,
  },
  methods: {},
};

</script>

<template>
  <div class="main">
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
</template>

<style>
.main {
  display: flex;
  flex-flow: column;
  align-items: center;
}
</style>
