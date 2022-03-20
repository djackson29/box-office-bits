<script>
export default {
  props: {
    movie: Object
  }
}

</script>

<template>

<article class="card">
  <p class="card__copy">{{ movie.Title }}</p>
  <img :src="" :alt="" class="">
  <p>{{  }}</p>

</article>

</template>



<style lang="scss" scoped>
</style>
