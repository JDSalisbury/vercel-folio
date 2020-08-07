<template>
  <v-parallax dark height="400" :src="require('../assets/download.jpeg')">
    <v-row align="end" class="fill-height">
      <v-col align-self="start" class="pa-0" cols="12">
        <v-avatar class="profile" color="grey" size="170" tile>
          <v-img :src="require('../assets/noodz.jpg')"></v-img>
        </v-avatar>
      </v-col>
      <v-col class="py-0">
        <v-list-item color="rgba(0, 0, 0, .4)" dark>
          <v-list-item-content>
            <v-list-item-title class="title">Jeff Salisbury</v-list-item-title>
            <v-list-item-subtitle>Software Engineer</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-col>
    </v-row>
  </v-parallax>
</template>

<script>
export default {}
</script>
