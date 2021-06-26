<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/my-work">My Work</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
  }
  body {
    background: #fff;
    font-family: 'Poppins', sans-serif;
    color: #333;
  }
</style>
