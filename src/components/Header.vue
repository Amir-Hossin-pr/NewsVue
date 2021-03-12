<template>
    <Carousel></Carousel>
</template>



<script>

import Carousel from './Carousel.vue'

export default{
    components:{
        Carousel
    },
    props:{
        carouselItems : []
    }  
}

</script>