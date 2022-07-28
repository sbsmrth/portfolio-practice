<template>
  <section class="main-links" id="experience">
    <div class="main-links__content">
      <p class="main-links__title">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nulla quis dolor magni
        natus quaerat. Vero nulla libero error non!
      </p>
      <p class="main-links__body">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta voluptate veniam
        assumenda recusandae, nihil, architecto modi animi ex obcaecati fugit saepe.
      </p>
      <div class="main-links__icons">
        <a href="https://github.com/sbsmrth" target="__blank">
          <img src="@/assets/img/github.png" alt="github icon">
        </a>
        <a href="https://www.linkedin.com/in/andr%C3%A9s-mart%C3%ADnez-henao/" target="__blank">
          <img src="@/assets/img/linkedin.png" alt="linkedin icon">
        </a>
      </div>
    </div>
  </section>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'MainLinksComponent',
});
</script>
