<template>
  <header class="navbar">
    <section class="navbar-section">
      <nuxt-link :to="{ name: 'index' }" class="avbar-brand mr-2">
        <h1>Nagesh</h1>
      </nuxt-link>
      <!-- <nuxt-link class="btn btn-link" :to="{ name: 'post' }"> POST </nuxt-link> -->
      <!-- <a href="..." class="btn btn-link">Docs</a>
      <a href="..." class="btn btn-link">GitHub</a> -->
    </section>
  </header>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<style>
.avbar-brand {
  color: #06b0f1;
}

a:visited {
  color: #06b0f1;
}

a:hover {
  color: #06b0f1;
}
</style>
