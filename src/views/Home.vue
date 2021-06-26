<template>
  <div class="home-page-container">
    <div class="intro-text-container">
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
  height: 100vh;

  .intro-text-container {
    
    @include default-page-padding;
    .small-title {
      font-weight: 400;
      font-size: $font-m;
      font-style: italic;
      margin-bottom: $space-3xs;
      letter-spacing: 0.2rem;
      text-transform: uppercase;
    }
    .medium-title {
      font-weight: 600;
      font-size: $font-2xl;
      letter-spacing: 0.2rem;
      margin: $space-3xs 0;
      text-transform: uppercase;
    }
    .large-title {
      font-weight: 700;
      font-size: $font-5xl;
      letter-spacing: 0.2rem;
      text-transform: uppercase;
      
    }
    .separation-line {
      width: 94px;
      height: 2px;
      margin: $space-m 0;
      background: $white-blue;
    }
  }
}
</style>
