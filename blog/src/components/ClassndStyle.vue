
<template>
<div>
 <h3 class="homestyle">Style and class Binding </h3>
 <h2 v-bind:style="{color:'blue'}">Style Binding</h2>
 <!-- class or object ko bind -->
 <h3 v-bind:class="{display:show}">Class Bind with Object</h3>
 <h2 v-bind:class="[aclass]">Class bind with array</h2>

</div>

</template>
    
<script>


export default {
/* eslint-disable */   name: "ClassndStyle"
,

data(){
    return{///yha main function me jitne b events bna rahe hai unke variable yaha bnayege
        show:false,
        aclass:'arrayClass'
    }
}


}
</script>

<style scoped>
.homestyle{
    color:aqua
    }
    .display{
        background-color: brown;
    }
    .arrayClass{
        background-color: aqua;
    }
</style>