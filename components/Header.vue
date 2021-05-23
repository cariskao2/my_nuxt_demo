<template>
  <!-- Header -->
  <header id="header">
    <div class="inner">
      <!-- Logo -->
      <nuxt-link to="/" class="logo">
        <span class="symbol"><img src="~/assets/images/logo.svg" alt="" /></span
        ><span class="title">Phantom</span>
      </nuxt-link>

      <!-- Nav -->
      <nav>
        <ul>
          <li><a href="#menu">Menu</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>
<style lang="scss" scoped>
  #header {
    .title {
      background-color: pink;
    }
  }
</style>