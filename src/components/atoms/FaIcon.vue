<template>
  <i class="fa-solid fa-bars fa-lg nav__icon" :class="{'fa-xmark': isOpen}"></i>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  props: {
    isOpen: {
      type: Boolean,
      required: true,
    },
  },
});
</script>
