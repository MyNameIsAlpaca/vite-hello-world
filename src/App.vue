
<script>

import Header from "./components/header.vue"

import Jumbo from "./components/jumbo.vue"

export default {
  data() {
    return {
    };
  },
  components: {
    Header,
    Jumbo,
  },
  methods: {},
};

</script>

<template>
  <div class="main">
    <Header></Header>
    <Jumbo></Jumbo>
  </div>
</template>

<style>
.main {
  display: flex;
  flex-flow: column;
  align-items: center;
}
</style>
