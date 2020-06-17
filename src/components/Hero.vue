<template>
  <div>
    <section class="hero is-fullheight has-background">
      <img class="hero-background" src="https://lh3.googleusercontent.com/pw/ACtC-3fhJV6fnONp9hkC0621annrlo7nZhLWf4nK9lchyM3tS-o0G4nN9qli5FujHAfhbKoIRofEIEJxlTJ7r5-YRBvHR-wH-C-CJIWFEzcvd6PBgp_gerLQxvxIXev6UwZbZzjol7VIlZnC4twf7VUS9z_vLw=w2394-h1596-no?authuser=0" alt="">
      <div class="hero-head">
      </div>
      <div class="hero-body">
          <div class="container has-text-centered">
              <div class="column is-6 is-offset-3">
                  <h1 class="title">
                      Em construção
                  </h1>
                  <h2 class="subtitle">
                      Jaca direto do Vale Encantando.
                  </h2>
                  <div class="box">
                      <div class="field is-grouped">
                          <p class="control is-expanded">
                              <input class="input" type="text" placeholder="Deixe seu email">
                          </p>
                          <p class="control">
                              <a class="button is-info">
                                  Quero saber
                              </a>
                          </p>
                      </div>
                  </div>
              </div>
          </div>
      </div>
    </section>
  </div>
</template>

<script>

export default {
  name: 'Hero'
}
</script>

<style scoped>
.hero-has-background {
  position: relative;
  overflow: hidden;
}
.hero-background {
  position: absolute;
  object-fit: cover;
  object-position: center center;
  width: 100%;
  height: 100%;
  opacity: 0.67;
}
.title {
  color: #17301C;
  font-size:  5rem;
}
.subtitle {
  color: #17301C;
  font-size:  2rem;
}
</style>
