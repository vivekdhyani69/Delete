<template>
<div>
   <!-- with the help of this v-html directory we prints a element which is insise in a another function -->
   <p v-html="rowhtml"></p>

<h1>Home Components</h1>
<h3>{{name}}</h3>
<h1>{{a+b}}</h1>

<Husers />
<HProduct />

</div>

</template>
    
<script>
import Husers from './Husers'///Ab hum yha AppVue jesa Environment bnayege  
import HProduct from './HProduct'


export default {
   /* eslint-disable */ name:'Home',    
    components:{
    Husers,
    HProduct,
    HProduct

},
data(){/////vue me ye ek tarike ka main function hai

   return {

      name:'Anil',
      a:10,
      b:10,
 rowhtml:"<h1>We are prints inside a main fun of vue</h1>"

   }
}


}
</script>

<style scoped>

div{background-color:lightblue;
height:500px;
}
</style>
