<template>
  <div class="card game-card">
    <div class="image-wrapper">
      <img :src="result.background_image"  @click="selectGame"/>
    </div>
    <div class="info-wrapper flex-col">
       <h3>{{ result.name }}</h3>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'GameCard',
    props: {
      result: {}
    }
  }
</script>
