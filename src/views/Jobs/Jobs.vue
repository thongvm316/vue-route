<template>
  <h2>Jobs</h2>
  <div v-for="job in jobs" :key="job.id">
    <router-link :to="{ name: 'JobDetail', params: { id: job.id } }">
      <h2>{{ job.title }}</h2></router-link
    >
  </div>
</template>

<script>
export default {
  name: 'Jobs',
  data() {
    return {
      jobs: [
        { title: 'UX/UI', id: 1, details: 'lorem' },
        { title: 'ReactJs', id: 2, details: 'lorem' },
        { title: 'VueJs', id: 3, details: 'lorem' },
      ],
    }
  },
}
</script>

<style lang="scss" scoped></style>
