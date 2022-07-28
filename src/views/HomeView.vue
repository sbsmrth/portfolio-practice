<template>
  <main>
    <main-section-component/>
    <main-links-component/>
    <main-projects-component/>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import MainSectionComponent from '@/components/MainSectionComponent.vue';
import MainLinksComponent from '@/components/MainLinksComponent.vue';
import MainProjectsComponent from '@/components/MainProjectsComponent.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    MainSectionComponent,
    MainLinksComponent,
    MainProjectsComponent,
  },
});
</script>

<style scoped>
  #down {
    margin-top: 70px;
    background: red;
    width: 400px;
    height: 300px;
  }
</style>
