<script >
import ComicsCards from './ComicsCards.vue';

export default{
    components:{
        ComicsCards
    },
}
</script>

<template>
    <main>
        <div class="container black">
            <div class="main-content">
                <ComicsCards></ComicsCards>
            </div>
        </div>

        <div class="container blue">
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

    main{
        color: white;
        background-image: url('/img/jumbotron.jpg');
        min-height: 1400px;
        background-size: cover;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
    }

    .container.black{
        background-color: black;
        padding: 30px 0;
    }

    .container.blue{
       background-color: #0282F9;  
    }

    .main-content,
    .shop-items{
        max-width: 1080px;
        margin: 0 auto;
    }

    .shop-items{
        display: flex;
        align-items: center;
        padding: 45px 0;
    }

    ul.items{
        list-style: none;
        padding:0;
        margin:0;
        width:100%;
        display:flex;
        align-items: center;
        justify-content: space-between;
    }

    ul.items>li{
        display: flex;
        align-items: center;
        gap: 15px;
        text-transform: uppercase;
        font-size: 14px;
    }

    ul.items img{
        width: 50px;
    }

    li.shop img{
        width:35px;
    }
</style>