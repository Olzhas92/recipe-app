<script setup lang="ts">

</script>

<template>
    <main class="about">
      <section class="about__section">
        <h1 class="about__title">About Nuxtcipes:</h1>
        <p class="about__description">
          Nuxtcipes is a recipe application based on the dummyJSON API, created by John Komarnicki for
          the <span class="about__highlight">Build Modern Apps with Nuxt</span> course.
        </p>
      </section>
    </main>
</template>

<style lang="scss" scoped>
    .about {
      font-family: "Montserrat";
      
      &__section {
        max-width: 1200px;
        margin: 0 auto;
        padding: 5rem 1rem;
      }

      &__title {
        font-size: 3.75rem; // text-6xl
        font-weight: 800; // font-extrabold
        margin-bottom: 1.5rem;
        text-wrap: balance;
      }

      &__description {
        font-size: 1.25rem; // text-xl
        font-weight: 800; // font-extrabold
        margin-bottom: 1.5rem;
        max-width: 1024px; // max-w-screen-lg
        text-wrap: balance;
      }

      &__highlight {
        font-weight: bold;
      }
    }
</style>