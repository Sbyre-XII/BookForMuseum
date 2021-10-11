<template>
    <base-header />
    <slot>
    </slot>
    <base-footer />
</template>

<script>
import BaseFooter from './base-footer.vue';
import BaseHeader from './base-header.vue';

export default {
  name: "base_layout", components: {
    BaseHeader,
    BaseFooter
  },
}
</script>