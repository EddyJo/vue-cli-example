<template>
  <div>
    <h1>This is Home Page</h1>
    <Eddy  title="Home Title" nickname="메롱"/>
  </div>
</template>

<script>
import Eddy from '@/components/Eddy.vue';

export default {
  
  components: {
    Eddy
  }

}
</script>

<style scoped>
h1 {
  color: red;
  font-size: 20px;
}
</style>