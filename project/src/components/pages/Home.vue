<template>
    <div>
    <div class="contenu container">
      <h1>Bienvenue sur mon site</h1>
      <div class="row">
        <div class="col-sm-4">
          <Card content = "Le Coran" title = "La vérité" image="coran.jpg" link="/quran"/>
        </div>
        <div class="col-sm-4">
          <Card/>
        </div>
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
    }
</script>

<style lang="scss" scoped>

</style>