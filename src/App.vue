<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
  body {
    background: #fff;
    font-family: 'Poppins', sans-serif;
    color: #333;
  }
</style>
