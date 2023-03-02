<script >

import Card from './Card.vue';

export default{
    components:{
        Card
    },
    data(){
        return{
            cards:[
                {
                    "thumb": 'https://m.media-amazon.com/images/I/91ytkCTqkEL.jpg',
                    "price": "$19.99",
                    "series": 'Action Comics',
                    "type": "comic book"
                },
                {
                    "thumb": 'https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg',
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": 'https://www.guidafumettoitaliano.com/bundles/fumettoweb/Images/PersonaggioImages/Thumbnails/12ece95a4ed8fbd5d9a532505334a354.jpg',
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/m/1/m1brao003isbn_0_yiy7urxwk3f1ozy9.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://media-assets.wired.it/photos/615d77d6d8b66b13086cecd5/master/w_1600%2Cc_limit/Joker-silver-age.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://mycomics.it/wp-content/uploads/sites/16/2022/12/FUMBBNEOY0001.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BTMA028ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://m.media-amazon.com/images/I/51galZVEAtL.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1OMEG008ISBN_0.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://m.media-amazon.com/images/I/91wWOz7QoPS.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://m.media-amazon.com/images/I/51sZeblq1fL.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.starshop.it/media/catalog/product/cache/225e5fda4dc5652637d552768fc55c5c/import/02139CTWS0004.jpg",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    }
}
</script>

<template>
    <div class="comics">
        <Card v-for="(card, i) in cards" :key="i" :card="card" ></Card>
    </div>
    <!-- v-for="(card, i) in cards" :key="i" -->
</template>

<style scoped>
    .comics{
        display: flex;
        flex-wrap: wrap;
    }
</style>