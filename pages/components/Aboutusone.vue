<template>
    <b-carousel
    id="carousel"
    v-model="slide"
    :interval="3500"
    controls
    indicators
    style="text-shadow: 1px 1px 2px #333"
    @sliding-start="onSlideStart"
    @sliding-end="onSlideEnd"
    >
    <div>
        <b-carousel-slide >
            <h1>olzhas</h1>
            <h1>manap</h1>
            <h1>damira</h1>
        </b-carousel-slide>
    </div>
    </b-carousel>
</template>

<script>
import axios from 'axios'
export default {
    data() {
        return {
            Images: [],
            slide: 0,
            sliding:null
        }
    },
    methods: {
        onSlideStart(slide){
            this.sliding = true
        },
        onSlideEnd(slide){
            this.sliding = false
        }
    },
    async asyncData(){
        try{
            let {data} = await axios.get('https://jsonplaceholder.typicode.com/photos')
            return {Images: data}
        } catch(err){
            console.log(err)

        }
    }

}
</script>


<style scoped>

</style>