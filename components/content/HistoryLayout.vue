<template>
  <div class="historyLayout">
    historyLayout
  </div>
</template>
<script>
export default {
//   props: {
//     pageTitle: {
//       type: String,
//       default: 'a'
//     },
//   }
//     data() {
//     return {
//       active: true
//     }
//   },
//   computed: {
//     page() {
//       return this.$store.state.page
//     }
//   },
//   methods: {
//     link_commit(linkPath) {
//       this.active = true
//       this.$store.commit('pagePathSet', linkPath)
//       setTimeout(() => {
//         this.$router.push({ path: linkPath })
//       }, 500)
//     }
//   }
}
</script>
<style scoped lang="scss">
.historyLayout{
  position: relative;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 2rem;
}

</style>
