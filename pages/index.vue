<template>
  <div>
    <main-section/>
  </div>
</template>

<script>

// Page Sections
import MainSection from '~/components/index/MainSection.vue'

export default {
  components: {
    MainSection
  },
  head () {
    return {
      title: 'Aioh - Home',
      meta: [
        { hid: 'og:title', name: 'og:title', content: 'Aioh - Home' },
        { hid: 'og:image', name: 'og:image', content: '/img/social-default-banner.png' },
        { hid: 'og:image:type', name: 'og:image:type', content: 'image/png' },
        { hid: 'og:image:alt', name: 'og:image:alt', content: 'Aioh: O futuro da educação é agora! Você está preparado?' },
        { hid: 'description', name: 'description', content: 'Aioh: O futuro da educação é agora! Você está preparado?' }
      ]
    }
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 40px;
  color: #ffffff;
  padding-top: 30px;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: #ffffff;
  word-spacing: 5px;
  padding-top: 20px;
  padding-bottom: 15px;
}

</style>
