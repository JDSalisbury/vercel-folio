<template>
  <div>
    <ParaBanner bgImage="hexblue.png" />
    <div class="base">
      <Space />
      <Section image="windows_xp_bliss.jpg" />
      <Space />
      <Projects />
      <Space />

      <Section image="space-universe-stars.jpg" />
      <Space />

      <!-- <Section image="blugree.jpg" />
      <Space />

      <Section image="space-universe-stars.jpg" /> -->

      <!-- <Space /> -->
    </div>
    <ParaBanner bgImage="blugree.jpg" />
    <Footer />
    <particles-bg color="#ffffff" type="cobweb" :bg="true" />
  </div>
</template>

<script>
import { ParticlesBg } from 'particles-bg-vue'

export default {
  data: () => ({}),
  components: {
    ParticlesBg,
    ParaBanner: () => import('@/components/para-banner'),
    Section: () => import('@/components/section-card'),
    Space: () => import('@/components/space'),
    Footer: () => import('@/components/footer'),
    Projects: () => import('@/components/projects')
  }
}
</script>

<style scoped>
.base {
  padding: 20px;
}
.canvas {
  position: fixed !important;
  background-color: black !important;
}
.sections {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(345px, 1fr));
  grid-gap: 60px 5px;
}
</style>
