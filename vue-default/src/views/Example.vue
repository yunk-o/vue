<template>
    <!-- <div class="container" v-bind:class="{'active':isActive,'text-red':isRed}"> Class Binding</div> -->
    <div v-bind:style="styleObject">인라인 스타일 Binding</div>
</template>
<script>
export default {
 
    data(){
        return{
            styleObject:{
                backgroundColor:"yellow",
                color:"red",
                fontWeight:"bold"
            }
            // isActive:true,
            // isRed:true,
        };
    }
}
</script>
<style>
.container {
    width:100%; 
    height:100px;
}
.active {
    background: yellow;
    font-weight: bolder;
}
.text-red{
    color:red
}

</style>
