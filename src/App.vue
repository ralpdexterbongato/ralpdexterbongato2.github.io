<template>
  <div id="app">
    <header>
      <div class="header-container">
        <div class="mylogo">
          <h1>RALP DEXTER BONGATO</h1>
        </div>
        <div class="navs-container">
          <router-link to="/">Home</router-link>
          <router-link to="/about">About</router-link>
          <router-link to="/skills">Skills</router-link>
          <router-link to="/projects">Projects</router-link>
          <router-link to="/contact">Contact</router-link>
        </div>
      </div>
    </header>
    <router-view>
    </router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
@import './assets/css/mycss.css';
</style>
