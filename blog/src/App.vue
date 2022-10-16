<template>
<div id="app">
      <h1>Props in vue js</h1>
      
<!-- <img alt="Vue logo" src="./assets/logo.png"> -->
<!-- <HelloWorld />  -->
 <!-- <Basic /> -->
<!-- <Basic data="Vivek is here" msg="Dhyani is where" />  -->
<!-- <IfDirective /> --> 
<!-- <ForLoop /> -->
<!-- <Home /> -->

<!-- <ClassndStyle /> -->
<!-- <DataBinding /> -->
<!-- <ChildProps v-bind:users="users" />    yha Props pass kr dia ab ye child-component me update krdega -->
<ParentProps />
</div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
//import Basic from './components/Basic.vue'
//import IfDirective from './components/IfDirective.vue'
//import ForLoop from './components/ForLoop.vue'

//////////////////////////////////////Structue of Component////////////////////////////////////////////////
//import Home from './components/Home.vue'

//import ClassndStyle from './components/ClassndStyle.vue'
//import DataBinding from './components/DataBinding.vue'
//import ChildProps from './components/ChildProps'
import ParentProps from './components/ParentProps'

export default {
    name: 'App',
    components: {
   
    // HelloWorld,
    //Basic,
    //IfDirective,
    // ForLoop
    //////////////////////Structure///////////////////////////////////
    // Home
    //ClassndStyle
    //DataBinding///Means yha register kr de
     //ChildProps
    ParentProps
},
data(){
    return{users:[
        {name:"Anil"},
        {name:"Sumit"},
        {name:"Karun"},
        {name:"Shyam"}
    ]

    }
}
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
