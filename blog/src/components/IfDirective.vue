<template>
<div>
<h1 v-if="show">Condition Rendering in if Block vue js</h1>
<!-- v-if is a directive jo ki Special Keywords -->
<h1 v-else>Condition Rendering in else block vue js</h1>
<button v-on:click="display">Toggle Element</button>


</div>

</template>
    
<script>
export default {
    name:'IfDirective',
    data(){
        return{show:true}///That is show and hide 
    },

methods:{//method is a object
display(){
    this.show=!this.show////
}
}
    
}
</script>