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
    <div class="effect-ice-berg-container">
      <img :src="iceBerg" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      iceBerg: require('@/assets/effects/ice-berg.svg') 
    }
  }
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
      font-size: $font-s;
      margin-bottom: $space-3xs;
      letter-spacing: 0.3rem;
      text-transform: uppercase;
    }
    .medium-title {
      font-weight: 600;
      font-size: $font-xl;
      letter-spacing: 0.5rem;
      margin: $space-3xs 0;
      text-transform: uppercase;
    }
    .large-title {
      font-weight: 600;
      font-size: $font-4xl;
      letter-spacing: 0.5rem;
      text-transform: uppercase;
      
    }
    .separation-line {
      width: 94px;
      height: 2px;
      margin: $space-m 0;
      background: $white-blue;
    }
  }
  .effect-ice-berg-container {
    position: absolute;
    bottom: 0;
    left: 0;
    //object-fit: cover;
    width: 100%;
    overflow: auto;
  }
}
</style>
