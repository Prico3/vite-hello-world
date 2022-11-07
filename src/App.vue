<script>
import AppBannerVue from './components/AppBanner.vue';

export default {
  data() {
    return {

    }
  },
  components: {
    AppBannerVue
  }
}
</script>

<template>
  <h1>Questa è la mia prima app con <em>Vite</em> + <em>Vue</em> </h1>
  <AppBannerVue />
</template>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body {
  background-color: black;
}

h1 {
  text-align: center;
  color: aquamarine;
}
</style>