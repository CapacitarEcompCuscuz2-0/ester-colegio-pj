<template>
    <div id="home">
        <Swiper class="swiper" :options="swiperOption">
            <SwiperSlide></SwiperSlide>
            <SwiperSlide></SwiperSlide>
            <SwiperSlide></SwiperSlide>
            <div class="swiper-pagination" slot="pagination"></div>
        </Swiper>
    </div>
</template>

<script>
import {Swiper, SwiperSlide} from 'vue-awesome-swiper'
import 'swiper/css/swiper.css'

export default {
    name: 'swiper',
    title: 'Space Between Slides',
    components: {
        Swiper,
        SwiperSlide
    },
    data() {
        return {
            swiperOption: {
                spaceBetween: 0,
                centeredSlides: true,
                autoplay: {
                    delay: 3500,
                    disableOnInteraction: false
                },
                pagination: {
                    el: '.swiper-pagination',
                    clickable: true
                }
            }
        }
    }
}
</script>

<style lang="scss" scoped>
    @import 'swiper/swiper.scss';
    #home{
        width: 100%;
        height: 86.6vh;
        padding-top: 13.4vh;
    }

    .swiper-container{
        height: 86.6vh;
    }

    .swiper-slide{
        background-image: url('slide1.png');
        background-size: cover;
        width: 100%;
        background-position: center -15vh;
    }
</style>