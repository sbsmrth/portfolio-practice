<template>
  <header>
    <nav class="nav">
      <button @click="manageNav" class="nav__button">
        <fa-icon :isOpen="showMenu"></fa-icon>
      </button>
      <ul id="items" :class="[{ 'nav__items--active' : showMenu }, 'nav__items']">
        <li class="nav__element">
          <a href="#banner">Home</a>
        </li>
        <li class="nav__element">
          <a href="#experience">Experience</a>
        </li>
        <li class="nav__element">
          <a href="#projects">Projects</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
import { defineComponent } from 'vue';
import FaIcon from '@/components/atoms/FaIcon.vue';

export default defineComponent({
  name: 'NavBarComponent',
  data: () => ({
    showMenu: false,
  }),
  components: {
    FaIcon,
  },
  methods: {
    manageNav() {
      this.showMenu = !this.showMenu;
    },
  },
});
</script>
