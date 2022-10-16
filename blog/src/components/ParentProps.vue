<template>
<div>
    <h3>Update to Parent Components</h3>
    <button v-on:click="updatetitle">Update Button</button>
    </div>
</template>
 
<script>
export default {
   name:'ParentProps',
   mehods:{
updatetitle(){
    //console.warn("Hello from title")
}

   }
}
</script>