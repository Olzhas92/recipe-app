<script setup lang="ts">

</script>

<template>
    <header class="header">
      <nav class="header__nav">
        <NuxtLink to="/" class="header__logo">
          <img class="header__logo-img" src="/icon-green.png" alt="" />
          <span class="header__logo-text">Nuxtcipes</span>
        </NuxtLink>
        <ul class="header__menu">
          <li class="header__menu-item">
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li class="header__menu-item">
            <NuxtLink to="/about">About</NuxtLink>
          </li>
        </ul>
      </nav>
    </header>
</template>

<style lang="scss" scoped>
    .header {
      padding: 1rem 0;
      border-bottom: 1px solid #ddd;
      font-family: "Montserrat";
    
      &__nav {
        display: flex;
        align-items: center;
        justify-content: space-between;
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 1rem;
      }

      &__logo {
        display: flex;
        align-items: center;
        gap: 0.25rem;
        text-decoration: none;

        &-img {
          width: 3.5rem;
        }

        &-text {
         font-size: 1.875rem; // text-3xl
         font-weight: bold;
         color: black;
        }
     }
     
     &__menu {
         display: flex;
         align-items: center;
         justify-content: flex-start;
         flex-direction: row;
         gap: 1.5rem;
         margin-left: auto;
         font-size: 1.25rem; // text-xl
         font-weight: bold;
         text-transform: capitalize;

         &-item {
          & a {
            text-decoration: none;
            color: inherit;
          }
         }
       }
    }
</style>