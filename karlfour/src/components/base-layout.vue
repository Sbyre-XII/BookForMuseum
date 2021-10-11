<template>
    <base-header />
    <slot>
    </slot>
    <base-footer />
</template>

<script>
import BaseFooter from '../ShopPage/base-footer.vue';
import BaseHeader from '../ShopPage/base-header.vue';

export default {
  name: "base_layout", components: {
    BaseHeader,
    BaseFooter
  },
}
</script>