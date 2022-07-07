<!-- HTML -->
<template>
    <div class="jumbotron">
        <img src="../assets/img/jumbotron.jpg" alt="jumbotron-img">
        
    </div>
    
</template>

<!-- JAVASCRIPT -->
<script>
export default {
    name: 'JumbotronBanner'
}
</script>


<!-- CSS -->
<style lang="scss" scoped>
.jumbotron{
    
    img{
        height: 350px;
        display: block;
        object-fit: cover;
        object-position: top;
    }
}


</style>