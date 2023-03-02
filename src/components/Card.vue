<script >

export default{
   props:{
        card:{
            type: Object,
            required: true
        }
   }
}
</script>

<template>

    <div class="card">
        <img :src="card.thumb" alt="img-Comics">
        <h3 class="card-text">{{card.series}}</h3>
    </div>

</template>

<style scoped>
    .card{
        max-width: 160px;
        padding: 10px;
        text-align: center;
    }

    .card img{
        width: 100%;
        aspect-ratio: 1/1.5;
    }

    .card-text{
        text-transform: uppercase;
        font-weight: 400;
        font-size: 16px;
    }

</style>