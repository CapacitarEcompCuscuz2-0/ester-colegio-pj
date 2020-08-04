<template>
    <div id="home">
        <Swiper class="swiper" :options="swiperOption">
            <SwiperSlide>
                <strong><h1>FAÇA JÁ SUA<br>MATRÍCULA!</h1></strong>
            </SwiperSlide>
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
        background-color: #EAE1E1;
    }

    h1{
        color: white;
        text-align: left;
        margin-left: 3%;
        margin-top: 23vh;
        font-size: 4rem;
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