<template>
  <div class="home-page-container">
    <div class="intro-text">
      <div class="medium-title">
        Henrik Oddløkken
      </div>
      <div class="large-title">
        Frontend developer
      </div>
      <div class="separation-line" />
      <div class="small-title">
        With a passion for
      </div>
      <div class="medium-title">
        Interaction Design
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
}
</script>

<style lang="scss" scoped>
.home-page-container {
  background: $sky-gradient;
  width: 100%;
  height: 100vh;

  .intro-text {
    color: $white-blue;
    font-weight: 600;
    .small-title {
      font-size: $font-l;
      letter-spacing: 0.2rem;
      text-transform: uppercase;
    }
    .medium-title {
      font-size: $font-2xl;
      letter-spacing: 0.2rem;
      text-transform: uppercase;
    }
    .large-title {
      font-size: $font-5xl;
      letter-spacing: 0.2rem;
      text-transform: uppercase;
      
    }
    .separation-line {
      width: 94px;
      height: 2px;
      background: $white-blue;
    }
  }
}
</style>
