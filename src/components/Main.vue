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
        <div class="container">
            <div class="main-content">
                {{message}}
            </div>

            <div class="shop-items">
                <ul class="items">
                    <li>
                        <img src="/img/buy-comics-digital-comics.png" alt="">
                        <p>Digital comics</p>
                    </li>
                    <li>
                        <img src="/img/buy-comics-merchandise.png" alt="">
                        <p>Dc merchandise</p>
                    </li>
                    <li>
                        <img src="/img/buy-comics-subscriptions.png" alt="">
                        <p>subscription</p>
                    </li>
                    <li class="shop">
                        <img src="/img/buy-comics-shop-locator.png" alt="">
                        <p>comic shop locator</p>
                    </li>
                    <li>
                        <img src="/img/buy-dc-power-visa.svg" alt="">
                        <p>dc power visa</p>
                    </li>
                </ul>
            </div>
        </div>
    </main>

</template>

<style scoped>
    .container{
        background-color: #0282F9;
        color: white;
    }

    .main-content{
        min-height: 100px;
        background-color: black;
        color: white;
    }

    .shop-items{
        display: flex;
        align-items: center;
        padding: 45px 0;
    }

    ul.items{
        list-style: none;
        margin:0;
        width:100%;
        display:flex;
        align-items: center;
        justify-content: space-between;
    }

    ul.items>li{
        display: flex;
        align-items: center;
        gap: 20px;
        text-transform: uppercase;
        font-size: 15px;
    }

    ul.items img{
        width: 50px;
    }

    li.shop img{
        width:35px;
    }
</style>