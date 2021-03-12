<template>
    <div >
        <div v-for="item in items" :key="item.id">

        </div>
    </div>
</template>

<script>
export default {
    items:[{
        Id:Number,
        Title:String,
        ImageName:String
    }]
}
</script>