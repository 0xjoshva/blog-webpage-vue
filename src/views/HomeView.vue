<template>
  <main id="main">
  <HomeLanding/>
  <HomeAbout/>
  <HomeBlue/>
  <HomeLaptop/>
  </main>
</template>

<script>
import HomeLanding from '@/components/HomeLanding.vue';
import HomeAbout from '@/components/HomeAbout.vue'
import HomeBlue from '@/components/HomeBlue.vue'
import HomeLaptop from '@/components/HomeLaptop'

export default {
  components: {
    HomeLanding, HomeAbout, HomeBlue, HomeLaptop,
}
}
</script>
<style scoped>
#main{
  background: var(--white);
}
</style>
