<script >
export default{
  data(){
    return{
        dcComicsItems:['Characters','Comics','Movies','TV','Games','Videos','News'],
        shop:['Shop Dc','Shop Dc Colllectibles'],
        dcItems:['Terms Of Use','Privacy policy(new)','Ad Choices','Advertising','jobs','Subscriptions','Talent Workshops','CPSC Certificates','Ratings','Shop Help','contact Us'],
        sitesItems:['DC', 'MAD Magazine', 'Dc Kids', 'Dc Universe', 'Dc Power visa']
    }
  },
}
</script>

<template>
    
    <footer>
        <div class="container">
            <section>
                <div class="menu-items">
                    <div class="col">
                        <h3>dc comics</h3>
                        <ul>
                            <li v-for="item in dcComicsItems">{{ item }}</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>Shop</h3>
                        <ul>
                            <li v-for="shopItem in shop">{{shopItem}}</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>Dc</h3>
                        <ul>
                            <li v-for="dcItem in dcItems">{{dcItem}}</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>Sites</h3>
                        <ul>
                            <li v-for="sitesItem in sitesItems">{{sitesItem}}</li>
                        </ul>
                    </div>
                </div>

                <div class="big-logo"></div>
            </section>
        </div>

        <div class="contact-us">
            <div class="row">
                <div class="col sing">
                    <button>Sing-Up now!</button>
                </div>

                <div class="col social">
                    <h2>Follow us</h2>
                    <ul>
                        <li>
                            <img src="/img/footer-facebook.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-twitter.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-youtube.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-pinterest.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-periscope.png" alt="">
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
    ul{
        list-style: none;
        padding:0;
    }

    footer{
        color:white;
    }

    .container{
        background-image: url('/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
    }

    section{
        max-width: 1080px;
        margin: 0 auto;
        max-height: 450px;
        display:flex;
        justify-content: space-between;
    }

    .big-logo{
        background-image: url('/img/dc-logo-bg.png');
        flex-basis: 52%;
        background-position: center;
    }

    .menu-items{
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        gap: 10px 20px;
        padding: 20px 0;
    }

    .menu-items h3,
    .col.social h2,
    button{
        text-transform: uppercase;
    }

    .menu-items ul{
        color: grey;
        font-size: 14px;
        line-height: 25px;
    }

    .col.sing button{
        background-color: transparent;
        color: white;
        border: 2px solid #0282F9;
        border-radius: 0px;
    }

    .contact-us{
        background-color:#303030;
    }

    .contact-us>.row{
        max-width: 1080px;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .row .col.social{
        display: flex;
        align-items: center;
        gap: 20px;
    }

    .col.social h2{
        color:#0282F9;
    }

    .col.social ul{
        display: flex;
        gap: 15px;
    }
</style>