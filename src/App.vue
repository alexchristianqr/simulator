<template>
  <div id="app" class="container-fluid">
    <AppSimulator />
  </div>
</template>

<script>
import AppSimulator from "@/components/AppSimulator";

export default {
  name: 'App',
  components: {
    AppSimulator,
  }
}
</script>


<style lang="scss">
/** Styles app */
@import 'assets/scss/style.scss';
</style>
