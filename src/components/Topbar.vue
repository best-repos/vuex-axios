<template>
  <div class="topbar">
    <mu-appbar :title="text" >
        <mu-icon-button icon='keyboard_arrow_left' @click="back"  slot="left"/>
        
    </mu-appbar>
  </div>
</template>

<script>
export default {
  data(){
      return{
          text:'笑话'
      }
  },
  methods:{
      back(){
        this.$router.go(-1)
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style  lang="scss"> 

</style>
