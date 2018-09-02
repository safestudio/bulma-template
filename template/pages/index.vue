<template>
  <section class="hero is-primary is-fullheight">
    <div class="hero-body">
      <div class="container has-text-centered">
        <app-logo/>
        <h1 class="title">
          {{ name }}
        </h1>
        <h2 class="subtitle">
          {{ description }}
        </h2>
        <div class="hero-section">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            class="button hero-button is-link is-outlined is-inverted">Nuxt.js Documentation</a>
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            class="button hero-button is-success is-outlined is-inverted">Nuxt.js GitHub</a>
        </div>
        <div class="hero-section">
          <a
            href="https://bulma.io/"
            target="_blank"
            class="button hero-button is-link is-outlined is-inverted">Bulma Documentation</a>
          <a
            href="https://github.com/jgthms/bulma"
            target="_blank"
            class="button hero-button is-success is-outlined is-inverted">Bulma GitHub</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>
<style>
.hero-button {
  margin-left: 5px;
  margin-right: 5px;
}
.hero-section {
  display: block;
  padding: 0.25rem;
}
</style>

