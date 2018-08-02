<template>
  <section class="container">
 <calculator/>
  </section>
</template>

<script>
import Calculator from '~/components/Calculator.vue'

export default {
  components: {
    Calculator
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}


</style>

