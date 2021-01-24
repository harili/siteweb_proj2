<template>
<div>
 <b-card
    :title="title"
    :img-src="'./images/'+image"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
     {{content}}
    </b-card-text>

    <b-button :href="link" variant="primary">Go somewhere</b-button>
  </b-card>
</div>
</template>

<script>

    export default {
    props: {
        title: {
            type: String,
            default: ""
        },
        content:{
            type:String,
            default:""
        },
        image:{
            type:String,
            default:""
        },
        link:{
            type:String,
            default:""
        }
    },
    mounted () {
        console.log({title :this.title, content : this.content, image: this.image});
    },
    }
</script>

<style lang="scss" scoped>

</style>