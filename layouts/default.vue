<template>
  <div class="app">
    <Header></Header>
    <nuxt />
  </div>
</template>

<script>
import Header from '~/components/Header.vue'


export default {
  components: {
    Header
  },
  mounted(){
 
  },
  destroyed() { // remove the JS code once the component has been destroyed
   
    }
}
</script>
<style>

</style>
