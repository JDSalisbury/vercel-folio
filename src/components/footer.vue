<template>
  <v-footer dark padless>
    <v-card flat tile class="indigo lighten-1">
      <v-card-text class="centered">
        <v-btn v-for="icon in icons" :key="icon" class="mx-4 spaced" icon>
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>
      </v-card-text>
      <v-card-text class="pt-0 center-text">
        Self-driven software developer, with excellent interpersonal skills,
        outstanding work ethics, and proof-based problem-solving capabilities.
        Recognized team player seeking to leverage Full-Stak knowledge to help
        companies become more efficient in their technological efforts.
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="centered">
        {{ new Date().getFullYear() }} — <strong>Salisbury</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: ['mdi-facebook', 'mdi-twitter', 'mdi-linkedin', 'mdi-instagram']
  })
}
</script>

<style scoped>
.centered {
  display: flex;
  justify-content: center;
}

.center-text {
  text-align: center;
}

.spaced {
  margin-left: 10px;
  margin-right: 10px;
}
</style>
