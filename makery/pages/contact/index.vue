<template>
    <div id='contact'>
        <div>
            <google-map class="col-12"></google-map>
        </div>

        <div class="col-12">
            <div class="row">
                <contact-us class="col-9"></contact-us>
                <div class="col-lg-3 pl-md-5 text-center">
                    <h2 class="weight-medium">
                        Find Us
                    </h2>							
                    <p>
                        <span style="color: #474747;">Phone:</span>
                        <br>
                        <span style="color: #727272;">0507-0079-9788</span>
                        <br>
                        <span>(09:00 ~ 18:00)</span>
                    </p>
                    <p>
                        <span style="color: #474747;">Email:</span>
                        <br>
                        <span style="color: #727272;">makery.kr@gmail.com</span>
                    </p>
                    <p>
                        <span style="color: #474747;">Address:</span>
                        <br>
                        <span style="color: #727272;"><small>서울, 광진구</small></span>
                        <br>
                        <span style="color: #727272;"><small>아차산로41길 5-4</small></span>
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

import GoogleMap from '~/components/contact/GoogleMap.vue';
import ContactUs from '~/components/contact/ContactUs.vue';

export default{
    layout:'makery',
    components :{
        'GoogleMap':GoogleMap,
        'ContactUs':ContactUs,
    }
}    
</script>

<style>

</style>
