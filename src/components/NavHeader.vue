<script >
export default{

  data(){
    return{
      navItems:['Characters','Comics','Movies','TV','Games','Collectibles','Videos','Fans','News','Shop',]
    }
  }
}
</script>

<template>

  <div class="nav-header">
    <div class="logo">
      <img src="/img/dc-logo.png" alt="">
    </div>

    <ul class="nav-items">
      <li v-for="navItem in navItems">
        {{ navItem }}
      </li>
    </ul>
  </div>

</template>

<style scoped>
  ul{
    list-style: none;
  }

  img{
    max-width:100%;
  }

  .nav-header{
    max-width: 1080px;
    margin: 0 auto;
    padding: 13px 0;
    display:flex;
    align-items: center;
    justify-content: space-between;
  }

  .nav-items{
    display: flex;
    gap: 20px;
    text-transform: uppercase;
    font-weight: 700;
  }

</style>