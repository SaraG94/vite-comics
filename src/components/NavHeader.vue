<script >
export default{
  data(){
    return{
      message:'content goes here'
    }
  },
}
</script>

<template>

  <div class="nav-header">
  
  </div>
  <div class="content">
    {{message}}
  </div>

</template>

<style scoped>
  .nav-header{
    /*debug*/
    min-height: 100px;
    min-width: 1280px;
    background-color: bisque;
  }

  .content{
    /*debug*/
    min-height: 100px;
    min-width: 1280px;
    background-color: black;
    color: white;
  }


</style>
