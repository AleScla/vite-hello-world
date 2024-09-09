<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'
export default {
  data() {
    return {
      count: 0
    }
  },
  components:{
    AppTitle,
    AppHero
  }
  
}
</script>

<template>
  
  <div>
    <AppTitle/>
    <button @click="count++">Click me {{ count }}</button>
  </div>

  <div>
    <AppHero/>    
  </div>
</template>

<style scoped>

</style>
