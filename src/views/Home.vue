<template>
  <div class="home">
    <div class="profile">
     <!--  <img class="profile-picture" src="@/assets/profile.png" alt=""> -->
      <h2 class="name">Hi, my name is Henrik Oddløkken</h2>
      <p class="about-short">
        I'm a frontend developer <br> specialising in interaction and UI -design
      </p>
      <button>Portfolio</button>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
}
</script>

<style lang="scss" scoped>
  .profile-picture {
    width: 256px;
  }
  .name {
    font-size: 1.5rem;
    margin: 0;
    font-weight: 400;
  }
  .about-short {
    margin: 0;
    font-size: 2.3rem;
    font-weight: bold;
  }
</style>
