<template>
  <b-container fluid>
    <b-row class="main-section" align-h="center" align-v="center">
        <b-col md="4">
          <logo/>
          <p></p>
          <h1 class="text-center">
            O futuro da educação é agora!
          </h1>
          <h2 class="text-center">
            Você está preparado?
          </h2>
        </b-col>
        <b-col md="1">
          <p></p>
        </b-col>
        <b-col md="5" class="video-frame-container">
          <b-embed class="video-frame" type="iframe"
           aspect="16by9"
           src="https://www.youtube.com/embed/NVv8T7ZKgbM"
           allowfullscreen
          ></b-embed>
        </b-col>
    </b-row>
</b-container>
</template>

<script>

import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style lang="css">
</style>
