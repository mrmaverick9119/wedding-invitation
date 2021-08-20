<template>
  <div id="gallery">
    <h1 class="uk-heading-line uk-text-center uk-h1 uk-padding-small title" uk-scrollspy="cls:uk-animation-slide-top-small"><span>Our Gallery</span></h1>
    <div class="uk-responsive-width uk-padding-large uk-overflow-hidden uk-padding-remove-top" uk-scrollspy="cls:uk-animation-slide-top-small">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/9chs5pHTKTQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="uk-padding-remove-top slider">
        <slick ref="slick" :options="slickOptions">
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-1.jpg" alt="KC-1">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-2.jpg" alt="foto 2">
            </div>
            <!-- <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-3.jpg" alt="foto 2">
            </div> -->
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-4.jpg" alt="foto 2">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-5.jpg" alt="foto 2">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-6.jpg" alt="foto 2">
            </div>
            <!-- <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-7.jpg" alt="foto 2">
            </div> -->
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-8.jpg" alt="foto 2">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-9.jpg" alt="foto 2">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-10.jpg" alt="foto 2">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-18.jpg" alt="foto 2">
            </div>
            <!-- <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-12.jpg" alt="foto 2">
            </div> -->
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-13.jpg" alt="foto 2">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-14.jpg" alt="foto 2">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
                <img src="../assets/images/KC-15.jpg" alt="foto 2">
            </div>
        </slick>
      </div>
    </div>
  </div>
</template>

<script>
import Slick from 'vue-slick'
import 'slick-carousel/slick/slick.css'
import 'slick-carousel/slick/slick-theme.css'

export default {
  name: 'Gallery',
  components: { Slick },

  data () {
    return {
      slickOptions: {
        infinite: true,
        slidesToShow: 3,
        slidesToScroll: 3,
        dots: true,
        speed: 400,
        autoplay: true,
        autoplaySpeed: 2000,
        responsive: [
            {
              breakpoint: 1024,
              settings: {
                slidesToShow: 3,
                slidesToScroll: 3,
                infinite: true,
                dots: true,
              }
            },
            {
              breakpoint: 600,
              settings: {
                slidesToShow: 2,
                slidesToScroll: 2,
                infinite: true,
                dots: true,
              }
            },
            {
              breakpoint: 480,
              settings: {
                slidesToShow: 1,
                slidesToScroll: 1,
                infinite: true,
                dots: false,
                fade: true,
                cssEase: 'linear',
              }
            }
        ]
      }
    }
  }
}
</script>

<style lang="css" scoped>
    #gallery {
        padding-top: 1px;
        background-color: #c1ebf7;
    } 
    .slider {
        padding: 15px;
    }

    @media screen and (max-width: 1024px) {
        .slider {
            padding: 3px;
        }
    } 
</style>