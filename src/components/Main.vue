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
                <button class="series">Current series</button>
                <ComicsCards></ComicsCards>
                <button class="load">Load more</button>
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
        min-height: 1500px;
        background-size: cover;
        background-position: top,center;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
    }

    .container.black{
        background-color: black;
    }

    .container.blue{
       background-color: #0282F9;  
    }

    .main-content,
    .shop-items{
        max-width: 1080px;
        margin: 0 auto;
    }

    .main-content{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-bottom: 15px;
    }

    button{
        background-color: #0282F9;
        color: white;
        text-transform: uppercase;
    }
    button.series{
        align-self: flex-start;
        font-size: 24px;
        padding: 10px 5px;
        margin-top: -30px;
    }

    button.load{
        padding: 15px 50px;
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