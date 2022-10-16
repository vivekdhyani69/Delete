<template>
<div>
<h1>For loop in java</h1>
<table border="1px" >
<tr>
    <td>id</td>
    <td>name</td>
    <td>email</td>
</tr>
<!-- that v-for is directive which is used to invokes for loop -->
<tr v-for="user in users"  :key="user.id" >
    <td>{{user.id}}</td>
    <td>{{user.name}}</td>
    <td>{{user.email}}</td>

</tr>


</table>
</div>

</template>
    
<script>
export default {
    name:"ForLoop",
    ///Firstly form data function
    data(){
        return{///return krege user ka array
            users:///That is a object of array
            [
{id:1,name:"Peter",email:"peter12@gmail.com"},
{id:2,name:"Toomy",email:"peter12@gmail.com"},
{id:3,name:"Crispy",email:"peter12@gmail.com"},
{id:4,name:"Mentos",email:"peter12@gmail.com"},
{id:5,name:"Talior",email:"peter12@gmail.com"}
     ]

        }
    }
   
    
}
</script>