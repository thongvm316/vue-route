<template>
  <h2>Job Detail Page</h2>
  <p>The job is {{ id }}</p>
  <div></div>
</template>

<script>
export default {
  name: 'JobDetail',
  props: ['id'],
  // data() {
  //   return {
  //     id: this.$route.params.id,
  //   }
  // },
}
</script>

<style lang="scss" scoped></style>
