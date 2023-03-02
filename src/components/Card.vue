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
        <p class="card-text"></p>
    </div>

</template>

<style scoped>
    .card{
        padding: 10px;
    }

    .card img{
        width: 160px;
        aspect-ratio: 1/1.5;
    }

</style>