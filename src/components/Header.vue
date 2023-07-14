<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div>

      <ul>
          <li>
              <RouterLink to="/">
                  <i class="fa fa-graduation-cap"></i>
                  Parcours scolaire</RouterLink>
          </li>
          <li>
              <RouterLink to="/">
                  <i class="fa fa-id-card"></i>
                  Parcours professionnel</RouterLink>
          </li>
          <li>
              <RouterLink to="/">
                  <i class="fa fa-file-code-o"></i>
                  Compétences</RouterLink>
          </li>
          <li>
              <RouterLink to="/">
                  <i class="fa fa-folder"></i>
                  Portfolio</RouterLink>
          </li>
      </ul>
  </div>
    <RouterView />
</template>

<style scoped>

  a{
      text-decoration: none;
      color: black;
      font-family: VT323;
      font-size: xx-large;
      transition: 0.5s;
  }

  a:hover{
      color: white;
  }

  div{
      height: 150px;
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