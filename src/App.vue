<template>
<div>
    
    <link :href="link.href" :rel="link.rel" :integrity="link.integrity" :crossorigin="link.origin">
    {{titulo}}
    <div class="row">
       <div class="col-md-3">oi</div>
      <div class="col-md-3">oi</div>
      <div class="col-md-3"><img :src="foto.url" alt="" srcset=""></div>
      <div class="col-md-3">oi</div>

    </div>
   
   
</div>
</template>
<script :src="script.src" :integrity="script.integrity" :crossorigin="script.origin"></script>
<script>
    export default{
      data(){
         return{
           titulo:'Hello world!',
           foto:{
             url:'/src/img/luffy.jpg'
           },
           link: {
             href:'https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css',
             rel:'stylesheet',
             integrity:'sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC',
             origin:'anonymous'
           },
           script:{
             src:'https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js',
             integrity:'sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM',
             origin:'anonymous'

           }

         }
      }
    }
</script>

<style >

</style>
