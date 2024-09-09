<script>
import AppHeader from './components/AppHeader.vue';

export default {
  data() {
    return {
      count: 0
    }
  },
  components:{
    AppHeader
  }
  
}
</script>

<template>
  <AppHeader/>
  <div>
    <button @click="count++">Click me {{ count }}</button>
  </div>
</template>

<style scoped>

</style>
