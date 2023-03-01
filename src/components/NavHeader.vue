<script >
export default{
  data(){
    return{
    
    }
  },
}
</script>

<template>

  <div class="nav-header">
    <div class="logo">
      <img src="/img/dc-logo.png" alt="">
    </div>
    <ul class="nav-items">
      <li>Characters</li>
      <li>Comics</li>
      <li>Movies</li>
      <li>TV</li>
      <li>Games</li>
      <li>Collectibles</li>
      <li>Videos</li>
      <li>Fans</li>
      <li>News</li>
      <li>Shop</li>
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