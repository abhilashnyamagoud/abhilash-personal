<template>
  <div class="home">
    <Details />
  </div>
</template>

<script>
import Details from '../components/Details/Details.vue'

export default {
  name: 'HomeView',
  components: {
    Details
  }
}
</script>
<style lang='css' scoped>
  .home{
    margin: 50px 0 0 0;
    padding: 20px;
    height: 100%;
  }
</style>