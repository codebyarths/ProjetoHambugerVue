<template>
  <Banner/>
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    
    <burgers-form/>
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import BurgersForm from '@/components/BurgersForm.vue';



export default{
  name: "Home",
  components:{
    Banner,
    BurgersForm
  }
}

</script>
