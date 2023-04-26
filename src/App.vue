<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div class="box">
    <AppTitle />
    <AppHero />
  </div>
</template>

<style scoped>
  .box{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;
  }
</style>
