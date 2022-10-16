<template>
<div>
    <h1>Hello from component vue</h1>
  
     <!-- <h2>{{data}}</h2>
     <h2>{{msg}}</h2>
      -->
      <h3>{{ok?"yes":"no"}}</h3>
      <button v-on:click="hello('Click to me')">Click On Button</button>
      <button v-bind:disabled="disablebtn" v-on:click="update">Click me</button>
     </div>
</template>

<script>
export default {
    /* eslint-disable */ 
     name:"Basic",
     props:{
        data:String,///That is defination part...uper se call ho raha App Vue pe
        msg:String,
        
       
    },
data(){
    ok:true
    disablebtn:"true"
},
methods:{//////Button click krane k lia yhi Prop chaiye
hello(data){///Calling a function with a events uper  se call ho raha
alert(data)
},


methods:{
   update(){
      this.ok=!this.ok
   }
}
            
        }
};
</script>