<template>
  <section class="index">
    <card v-for="i in 5" v-bind:key="i"/>
  </section>
</template>

<script>
import Card from '~/components/Card.vue'

export default {
  transition: 'slide-left',
  components: {
    Card
  }
}
</script>

<style scoped>
.index {
  display: flex;
  flex-wrap: wrap;
}
</style>