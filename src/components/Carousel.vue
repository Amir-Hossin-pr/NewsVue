<template>
    <div class="carousel">
        <div class="carouselContent" v-for="item in Items" :key="item.id">
            <h2>{{ item.Title }}</h2>
        </div>
    </div>

</template>

<script>
export default {
    props:{
        Items:[{
            id:Number,
            Title:String
        }]
    }
}
</script>

<style>
    @import '../sass/dist/_Layout.css'
</style>