<template lang="html">
  <b-container fluid>
      <b-row align-h="center">
        <b-col md="2">
          <b-link href="/">
            <b-img src="/img/logo.svg" fluid/>
          </b-link>
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
  }
}
</script>

<style lang="css">
</style>
