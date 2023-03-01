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

    <main>
        <div class="main-content">
            {{message}}
        </div>

        <div class="container">
            <div class="nav-main"></div>
        </div>
    </main>

</template>

<style scoped>

  .main-content{
    /*debug*/
    min-height: 100px;
    min-width: 1280px;
    background-color: black;
    color: white;
  }

 .container{
    /*debug*/
    min-height: 100px;
    min-width: 1280px;
    background-color: #0282F9;
    color: white;
  }
</style>