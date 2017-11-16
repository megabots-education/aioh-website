<template lang="html">
  <b-navbar toggleable="md" type="dark" variant="info" fixed="top">

    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
    <b-navbar-brand>
      <nuxt-link to="/">
        <img src="/img/logo.svg" alt="Aioh">
      </nuxt-link>
    </b-navbar-brand>

    <b-collapse is-nav id="nav_collapse">
      <!--
      <b-navbar-nav>
        <b-nav-item href="/">Home</b-nav-item>
      </b-navbar-nav>
      -->
      <b-navbar-nav class="ml-auto">
          <nuxt-link to="/signin" class="nav-link">
            Sign In
          </nuxt-link>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
}
</script>
