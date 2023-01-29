<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/abilities.vue'
</script>

<template>
    <div class="nav-container">
      
    <RouterLink to="/"><img src="https://upload.wikimedia.org/wikipedia/en/7/72/New_Mobile_Legends_Bang_Bang_2020_Logo.png" alt="" class="logo"></RouterLink>
    <!-- <h3>Lester Calunia</h3> -->

    <div class="nav-btn">
      <a><RouterLink to="/">Home</RouterLink></a>
      <a><RouterLink to="/abilities">Abilities</RouterLink></a>
      <a><RouterLink to="/gameplays">Gameplay</RouterLink></a>
    </div>

    </div>
  <RouterView />
</template>

<style scoped>
  .nav-container {
    margin: 0px;
    padding: 0px;
    width: 100%;
    height: 100px;
    background-color: rgba(0, 0, 0, 0.079);
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .nav-btn {
    width: 300px;
    display: flex;
    justify-content: space-evenly;
  }

  .nav-container h3{

    text-decoration: none;
    color: white;
    font-size: 100px;
  }
  .nav-container a{
    text-decoration: none;
    font-size: 25px;
    color: white;
  }
  .nav-container img:hover{
    background-color: rgb(26, 24, 24);
  }

  .logo {
    height: 50px;
    width: 150px;
    margin-left: 3em;
  }
</style>
