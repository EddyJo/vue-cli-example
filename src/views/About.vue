<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Eddy title="About Title" nickname="경현"/>
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