<template>
  <div class="topPage">
    <HeaderNav />
    <nuxt />
  </div>
</template>
<script>
import HeaderNav from '~/components/header/HeaderNav.vue'
export default {
  layout: 'topPage',
  components: {
    HeaderNav
  }
}
</script>
<style scoped lang="scss">
.topPage{
  width: auto;
  min-width: 100vw;
}
</style>
