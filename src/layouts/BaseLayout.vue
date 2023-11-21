<template>
  <!-- eslint-disable  -->
  <div>
    <BaseHeader>
      <slot name="header"></slot>
    </BaseHeader>
    <slot></slot>
    <BaseFooter>
      <slot name="footer"></slot>
    </BaseFooter>
  </div>
</template>

<script>
import BaseHeader from '@/components/Base/BaseHeader.vue';
import BaseFooter from '@/components/Base/BaseFooter.vue';

export default {
  components: { BaseHeader, BaseFooter },
};
</script>
