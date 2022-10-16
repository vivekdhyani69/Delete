<template>
<!-- h1 me thas message prints outside AREA and style me (white space preline) data dito line-line copy kr dega -->
    <h1 style="white-space:pre-line">{{message}}</h1>
 <!-- v-model= yha se krega jesa he hum textbox(vue-part hai ye) me kuch b type krege vo ye message me copy krta rahega -->
    <textarea type="text" v-model="message" />
</template>

<script>
export default {
    name:'DataBinding',
    data(){///that is model part (JS)
return{
message:'hi My '

}

    }
}
</script>