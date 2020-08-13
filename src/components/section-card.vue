<template>
  <v-card light class="mx-auto">
    <v-img
      class="white--text align-end"
      height="200px"
      :src="require('../assets/' + image)"
    >
    </v-img>
    <v-card-title>Doin Dope Shit</v-card-title>
    <v-card-subtitle class="pb-0">real dope</v-card-subtitle>

    <v-card-text class="text--primary">
      <div>
        Software developer, with excellent interpersonal skills, outstanding
        work ethic, and proof-based problem-solving capabilities. Recognized
        team player seeking to leverage knowledge to help companies become more
        efficient in their technological efforts.
      </div>
    </v-card-text>

    <v-card-actions>
      <v-btn color="orange" text>
        Share
      </v-btn>

      <v-btn color="orange" text>
        Explore
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  props: ['image']
}
</script>
