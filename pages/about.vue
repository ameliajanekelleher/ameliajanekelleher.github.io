<template>
  <section class="container">
    <div>
      <h1 class="title">
        About Me
      </h1>
      <p class="subtitle">
        I like to play with my friends, especially Logan, Ellie, Maisie and Lily-ann. I also like to play with my half-brother, who is called George.
      </p>
      <p class="subtitle">
        I love to play with my stuff from my birthday. I also love to play with my mum and dad with my 500 puzzle. I really love to play with my new yoyo as well.
      </p>
      <div class="links">
        <nuxt-link 
          to="/" 
          class="button--green">Home</nuxt-link>
        <nuxt-link 
          to="about" 
          class="button--grey">About</nuxt-link>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
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
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
