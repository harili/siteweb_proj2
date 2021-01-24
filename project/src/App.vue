<template>
  <div id="app">
 <b-navbar toggleable="sm" type="light" variant="dark">
    <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

    <b-navbar-brand>BootstrapVue</b-navbar-brand>
      <b-navbar-nav>
        <b-nav-item href="/">Home</b-nav-item>
        <b-nav-item href="/about">A propos</b-nav-item>
      </b-navbar-nav>

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
