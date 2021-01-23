<template>
  <div id="app">
 <b-navbar toggleable="sm" type="light" variant="dark">
    <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

    <b-navbar-brand>BootstrapVue</b-navbar-brand>

    <b-collapse id="nav-text-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-text>Navbar text</b-nav-text>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
    <router-view></router-view>
    
</div>
</template>

<script>

export default {
  name: 'App',

};
</script>

<style>

</style>
