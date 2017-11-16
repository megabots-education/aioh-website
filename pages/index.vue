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
