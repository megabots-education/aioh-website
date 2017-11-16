<template lang="html">
  <b-container fluid>
      <b-row align-h="center">
        <b-col md="2">
          <nuxt-link to="/">
            <b-img src="/img/logo.svg" fluid/>
          </nuxt-link>
          <p></p>
        </b-col>
      </b-row>
      <b-row align-h="center">
        <b-col md="3">
          <b-form @submit="onSubmit">
            <label for="inputEmail" class="sr-only">Email</label>
            <input type="email" id="inputEmail" class="form-control" placeholder="Email" required="" autofocus="">
            <p></p>
            <label for="inputPassword" class="sr-only">Senha</label>
            <input type="password" id="inputPassword" class="form-control" placeholder="Senha" required="">
            <p></p>
            <button class="btn btn-lg btn-primary btn-block" type="submit">Sign in</button>
          </b-form>
        </b-col>
      </b-row>
    </b-container>
</template>

<script>
export default {
  layout: 'cleam',
  data: {
    form: {
      email: '',
      secret: ''
    }
  },
  methods: {
    onSubmit (evt) {
      alert('Você não tem permissões para isto.')
    }
  },
  head () {
    return {
      title: 'Aioh - Sign in',
      meta: [
        { hid: 'og:title', name: 'og:title', content: 'Aioh - Sign in Page' },
        { hid: 'og:image', name: 'og:image', content: '/img/social-default-banner.png' },
        { hid: 'og:image:type', name: 'og:image:type', content: 'image/png' },
        { hid: 'og:image:alt', name: 'og:image:alt', content: 'Aioh: O futuro da educação é agora! Você está preparado?' },
        { hid: 'description', name: 'description', content: 'Faça seu login na plataforma online.' }
      ]
    }
  }
}
</script>

<style lang="css">
</style>
