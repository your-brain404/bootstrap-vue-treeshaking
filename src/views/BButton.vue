<template>
  <div class="buttons">
    <b-button>Button</b-button>
    <b-button variant="danger">Button</b-button>
    <b-button variant="success">Button</b-button>
    <b-button variant="outline-primary">Button</b-button>
  </div>
</template>

<script>
import { BButton } from "bootstrap-vue";
export default {
  components: {
    BButton,
  },
};
</script>

<style lang="scss">
@import "bootstrap/scss/buttons";
</style>