<template>
  <div class="main">
    <div class="base">
      <ParaBanner />
      <Space />
      <Section image="space-universe-stars.jpg" />
      <Space />
      <Section image="windows_xp_bliss.jpg" />
      <Space />
      <Section image="blugree.jpg" />
      <Space />
      <Section image="space-universe-stars.jpg" />
    </div>
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
    Space: () => import('@/components/space')
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
</style>
