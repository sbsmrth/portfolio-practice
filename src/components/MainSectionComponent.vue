<template>
  <section class="banner" id="banner">
    <article class="banner__info">
      <div class="banner__title">
        Lorem Ipsum
      </div>
      <div class="banner__text">
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolor sit at met
        </p>
      </div>
      <button class="banner__button">Activate</button>
    </article>
    <a class="banner__footer" href="#experience">
      <p class="banner__last">Learn more</p>
      <i class="fa-solid fa-arrow-down fa-lg banner__arrow"></i>
    </a>
  </section>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'MainSectionComponent',
});
</script>
