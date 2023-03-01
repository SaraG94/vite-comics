<script >
export default{
  data(){
    return{
     
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
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>Shop</h3>
                        <ul>
                            <li>Shop Dc</li>
                            <li>Shop Dc Colllectibles</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>Dc</h3>
                        <ul>
                            <li>Terms Of Use</li>
                            <li>Privacy policy(new)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>contact Us</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>Sites</h3>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>Dc Kids</li>
                            <li>Dc Universe</li>
                            <li>Dc Power visa</li>
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