<template>
  <div>
    <custom-header :width="width"></custom-header>
    <div :class="showleft">
      <nuxt/>
    </div>
    <custom-footer></custom-footer>
  </div>
</template>

<script>
import CustomHeader from '~/components/Header/Header.vue'
import CustomFooter from '~/components/Footer/Footer.vue'

export default{
    components :{
        'custom-header' : CustomHeader,
        'custom-footer' : CustomFooter
    },
    data:function(){
        return {
            width:0,
        }
    },
    beforeMount() {
        window.addEventListener('resize',()=>{
            this.width=window.innerWidth;
        });
    },
    mounted() {
      this.width=window.innerWidth;
    },
    computed:{
        showleft(){
            return this.width>1024?'page-lg':'page-sm'
        }
    },
}    
</script>

<style scoped>
.page-lg{
  padding-left: 270px;
  padding-right: 100px;
}

.page-sm{
  padding-left: 20px;
  padding-right: 20px;
  padding-top: 70px;
}
</style>

<style>
.margin-auto{
	margin-left: auto;
	margin-right: auto;
}
</style>