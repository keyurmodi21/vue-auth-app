<template>
  <div id="app">
    <navigation />
    <div class="container">
      <router-view />
    </div>
  </div>
</template>

<script>
import Navigation from "./Navigation";

export default {
  components: {
    Navigation
  }
};
</script>