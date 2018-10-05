<template>
    <div id="list">
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
            <poster class="col-lg-3 col-md-4 col-sm-12"></poster>
    </div>
</template>

<script>
import Poster from '~/components/List/Poster.vue'

export default{
    layout:'makery',
    components:{
        'Poster':Poster
    }
}    
</script>

<style scoped>
#list{
    display: flex;
    flex-wrap: wrap;
}
</style>
