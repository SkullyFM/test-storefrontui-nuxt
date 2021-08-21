<template>
  <SfCallToAction
    title="Subscribe to Newsletters"
    buttonText="Subscribe"
    link="/"
    description="Be aware of upcoming sales and events. Receive gifts and special offers!"
    background="#e1e3e2"
    image=""
  />
</template>

<script>
import { SfCallToAction } from "@storefront-ui/vue";
export default {
  components: {
    SfCallToAction
  }
}
</script>

<style lang="scss">
@import "~@storefront-ui/vue/styles";
:root {
  @include generate-color-variants(--_c-purple-primary, #bb1993);
  @include generate-color-variants(--_c-purple-secondary, #7e2971);
  @include assign-color-variants(--c-primary, --_c-purple-primary);
  @include assign-color-variants(--c-primary-variant, --_c-purple-secondary);
}
</style>
