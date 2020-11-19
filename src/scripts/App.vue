<template>
  <div class="app">
    <app-header class="header"></app-header>
    <background></background>
    <Form></Form>
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import Background from "./components/Background.vue";
import Form from "./components/Form.vue";

export default {
  components: { AppHeader, Background, Form },

  data: () => ({}),

  mounted() {},
};
</script>

<style lang="scss" scoped>
.app {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}

.header {
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
  height: 60px; // Defined in AppHeader as well, but repeating for reference
  background: white;
  z-index: 10;
}

.reveal {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}

.carousel {
  position: absolute;
  right: 0;
  bottom: 0;
  left: 0;
  top: 100%;
}
</style>
