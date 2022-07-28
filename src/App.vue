<template>
  <nav-bar-component/>
  <router-view/>
</template>

<script>
import { defineComponent } from 'vue';
import NavBarComponent from '@/components/NavBarComponent.vue';

export default defineComponent({
  name: 'App',
  components: {
    NavBarComponent,
  },
});
</script>

<style lang="scss">
  @import '@/assets/styles/main.scss';
</style>
