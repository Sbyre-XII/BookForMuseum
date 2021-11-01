<template>
    <base-header />
    <slot>
    </slot>
    <base-footer />
</template>

<script>
import BaseFooter from './BaseFooter.vue';
import BaseHeader from './BaseHeader.vue';

export default {
  name: "base_layout", components: {
    BaseHeader,
    BaseFooter
  },
}
</script>