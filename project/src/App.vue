<template>
  <div id="app">
    <b-navbar toggleable type="dark" variant="dark">
    <b-navbar-brand href="#">NavBar</b-navbar-brand>
    <b-navbar-toggle target="navbar-toggle-collapse">
      <template #default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">Link 1</b-nav-item>
        <b-nav-item href="#">Link 2</b-nav-item>
        <b-nav-item href="#" disabled>Disabled</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
    <div class="contenu container">
      <h1>Bienvenue sur mon site</h1>
      <div class="row">
        <div class="col-sm-4">
          <Card/>
        </div>
      </div>
   </div>
    
</div>
</template>

<script>
import Card from "@/components/Card"
export default {
  name: 'App',
  components:{
    Card,
  }
};
</script>

<style>

</style>
