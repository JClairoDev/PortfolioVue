<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div>
      <ul>
          <li>
              <RouterLink to="/">Parcours scolaire</RouterLink>
          </li>
          <li>
              <RouterLink to="/">Parcours professionnel</RouterLink>
          </li>
          <li>
              <RouterLink to="/">Compétences</RouterLink>
          </li>
          <li>
              <RouterLink to="/">Portfolio</RouterLink>
          </li>
      </ul>
  </div>
    <RouterView />
</template>

<style scoped>

  a{
      text-decoration: none;
      color: black;
  }

  div{
      height: 300px;
      width: 100%;
      background-color: coral;
  }
  ul{
      display: flex;
      gap : 2rem;
      justify-content: center;
      list-style: none;
  }

</style>