<template>
    <div id="invitation">
        <h1 class="uk-heading-line uk-text-center uk-h1 uk-padding-small title" uk-scrollspy="cls:uk-animation-slide-top-small"><span>Our Invitation</span></h1>
        <div class="uk-responsive-width uk-padding-large uk-overflow-hidden uk-padding-remove-top">
            <div class="text-nama">
                <h1 uk-scrollspy="cls:uk-animation-slide-top-small">Kishan Kumar C</h1>
                <h5 uk-scrollspy="cls:uk-animation-slide-top-small">S/O</h5>
                <h5 uk-scrollspy="cls:uk-animation-slide-top-small">Padmashali saddam smt v. Kalavathi &amp; Sri S.R. Chandrashekar </h5>
                <h4 uk-scrollspy="cls:uk-animation-slide-top-small">Weds</h4>
                <h1 uk-scrollspy="cls:uk-animation-slide-top-small">Chaithra S G</h1>
                <h5 uk-scrollspy="cls:uk-animation-slide-top-small">D/O</h5>
                <h5 uk-scrollspy="cls:uk-animation-slide-top-small">Padmashali seerpu smt G. Thulasi &amp; Sri S.N Gopinath</h5>
            </div>
            <div class="uk-responsive-width uk-padding-large uk-padding-remove-bottom">
                <h2>Wedding Reception</h2>
                <p>Tuesday, 31 August 2021<br>5:00 PM Onwards</p>
            <div/>
                <h2>Wedding day</h2>
                <p>Wednesday, 1 September 2021<br>7:20 AM </p>
                <div class="countdown uk-flex uk-visible@l">
                    <div uk-grid uk-countdown="date: 2021-08-31T05:00:00+05:30" class="uk-margin-auto">
                        <div>
                            <div class="uk-countdown-number uk-countdown-days"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Days</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-hours"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Hours</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-minutes"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Minutes</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-seconds"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Seconds</div>
                        </div>
                    </div>
                </div>
                
                <div class="countdown uk-flex uk-hidden@l">
                    <div uk-grid uk-countdown="date: 2021-08-31T05:00:00+05:30" class="uk-margin-auto">
                        <div>
                            <div class="uk-countdown-number uk-countdown-days"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Days</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-hours"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Hours</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-minutes"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Minutes</div>
                        </div>
                        <div class="uk-countdown-separator">:</div>
                        <div>
                            <div class="uk-countdown-number uk-countdown-seconds"></div>
                            <div class="uk-countdown-label uk-margin-small uk-text-center">Seconds</div>
                        </div>
                    </div>
                </div>
                <h1>Best are those moments that are shared with our loved ones.<br/> We are thrilled to inform that we are getting married and we heartfully request the honour of <br/>your presence at our marriage ceremony.</h1>
                <div class="uk-responsive-width uk-padding-large uk-padding-remove-bottom"/>

            
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3888.372554231773!2d77.4924786!3d12.947996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bae3ebbf87d1e6d%3A0x19b1563835f704d3!2sJnana%20Ganapati%20Temple%20%2F%20Jnana%20Ganapati%20Kala%20Bhavana!5e0!3m2!1sen!2sin!4v1629460977260!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy">img title="Directions" uk-tooltip="pos: bottom" class="uk-width-1-4" src="../assets/images/maps.png" alt="Maps"></iframe>
                
                <div class="uk-responsive-width uk-padding-large uk-padding-remove-bottom"/>
                <p class="text-nama">Crafted by Kishan with lots of <i uk-icon="icon: heart"></i> for Chaithra</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Invitation',
};
</script>

<style lang="scss" scoped>
    $colorprimary : #dd183f;

    #invitation {
        padding-top: 1px;
        padding-bottom: 50px;
        background-color: #c1ebf7;
    }
    .countdown  * {
        font-size: 30px !important;
        color: $colorprimary !important;
    }
    .uk-countdown-number, .uk-countdown-separator {
        line-height: 1 !important;
    }
    .countdown .uk-countdown-label {
        font-size: 20px !important;
    }
    .countdown .uk-grid > * {
        padding-left: 10px !important;
    }
    .text-nama {
        padding-top: 10px;
        padding-bottom: 10px !important;
    }
    .text-nama h1{
        font-size: 50px !important;
        margin: 0 !important;
    }
    .text-nama h5, .text-nama h3 {
        margin: 0 !important;
    }
    .text-nama p,.text-nama h4 {
        padding-top: 10px !important;
        padding-bottom: 10px !important;
    }
    .uk-width-1-4 {
        padding: 0 !important;
        margin: 0 !important;
    }
    h4 {
        margin-top: 15px !important;
    }
    h5 {
        color: #666666 !important;
    }

    @media screen and (max-width: 1024px) {
        .countdown  * {
            font-size: 20px !important;
            color: $colorprimary !important;
        }
        .uk-countdown-number, .uk-countdown-separator {
            line-height: 1 !important;
        }
        .countdown .uk-countdown-label {
            font-size: 12px !important;
        }
        .countdown .uk-grid > * {
            padding-left: 5px !important;
        }
        .text-nama h1 {
            font-size : 27px !important;
        }
        .text-nama h5 {
            font-size : 12px !important;
        }
    }
</style>
