<!-- HTML -->
<template>
    <div class="card">
        <img :src="infoCard.thumb" :alt="infoCard.type">

        <h3>{{ infoCard.series}}</h3>

    </div>
        
        
    
</template>

<!-- JAVASCRIPT -->
<script>
export default {
    name: 'SeriesCard',
    props: {
        infoCard: Object
    }
    
}
</script>

<!-- CSS -->
<style lang="scss" scoped>
.card{
    width: calc((100% / 6) - 20px);
    margin: 10px;

    img{
        width: 100%;
        aspect-ratio: 1/1;
        object-fit: cover;
        object-position: top;
    }

}

</style>