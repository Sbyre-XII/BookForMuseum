<template>
    <base-header />
    <slot>
    </slot>
    <base-button />
    <base-footer />
</template>

<script>
import BaseFooter from './base-footer.vue';
import BaseHeader from './base-header.vue';
import BaseButton from './base-button.vue';

export default {
  name: "base_layout", components: {
    BaseHeader,
    BaseFooter,
    BaseButton
  },
}
</script>