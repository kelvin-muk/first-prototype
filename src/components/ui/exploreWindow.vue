<template>
  <div class="explore-window">
    <div class="explore-window__button">
      <!-- <Explore /> -->
      <h3 id="explore-text">EXPLORE</h3>
      <Eclipse />
    </div>
    <div class="explore-window__block"></div>
  </div>
</template>

<script>
  import Explore from '@/assets/icons/explore-text'
  import Eclipse from '@/assets/icons/explore-eclipse'

  export default {
    components: {
      Explore,
      Eclipse
    }
  }
</script>
