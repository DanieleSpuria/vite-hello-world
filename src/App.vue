
<script>
import AppTitle from './components/AppTitle.vue'

export default {
  name: 'App',
  components: {
    AppTitle
  }
}
</script>

<template>
  <div class="box">
    <AppTitle />
  </div>
</template>

<style scoped>
  .box{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
</style>
