<template>
<b-container fluid>
  <!-- Content here -->
  <b-navbar toggleable="lg" type="light" class="navbar">
    <b-navbar-brand to="/">
      <img class="logo" src="@/static/logo-zito.png" alt="Zito-WebDesign Logo">
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse">
    </b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav type="light">

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item to="leistungen">Leistungen</b-nav-item>
        <b-nav-item to="referenzen">Referenzen</b-nav-item>
        <b-nav-item to="kontakt">Kontakt</b-nav-item>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</b-container>
</template>

<script>
export default {

}
</script>

<style lang="scss">
  .navbar {
    background: #fff;
  }
  .logo {
    max-width: 10rem;
  }
</style>
