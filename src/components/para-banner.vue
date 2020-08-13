<template>
  <v-parallax dark height="400" :src="require('../assets/' + bgImage)">
    <v-row align="end" class="fill-height">
      <v-col align-self="start" class="pa-0" cols="11">
        <v-avatar class="profile" color="grey" size="200" tile>
          <v-img :src="require('../assets/noodz.jpg')"></v-img>
        </v-avatar>
      </v-col>
      <v-col class="py-0">
        <v-list-item color="rgba(0, 0, 0, .4)" dark>
          <v-list-item-content class="">
            <v-list-item-title class="title">Jeff Salisbury</v-list-item-title>
            <v-list-item-subtitle>Software Engineer</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-col>
    </v-row>
  </v-parallax>
</template>

<script>
export default {
  props: ['bgImage']
}
</script>

<style scoped>
.title-bubble {
  background-color: #000000d4;
  padding-right: -13px;
  margin-right: 810px;
  padding-left: 20px;
  border-radius: 58%;
}
</style>
