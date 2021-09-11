<template>
    <div>
        <!-- <h1 v-if="bRender">bRender값이 true이면, h1 블록이 화면에 보여지게 됩니다.</h1>
        <h1 v-else>bRender값이 false이면, h1 블록이 화면에 보여지게 됩니다.</h1> -->

        <!-- <h1 v-if="type=='A'">A</h1>
        <h1 v-else-if="type=='B'">B</h1>
        <h1 v-else-if="type=='C'">C</h1>
        <h1 v-else>Oth er</h1> -->

        <h1 v-show="bRender">A</h1>
    </div>
</template>
<script>
export default {
    name:'',
    components:{},
    data(){
        return{
            // bRender:false

            // type:"f"

            bRender:true
        };
    },
    setup() {},
    create() {},
    mounted() {},
    unmounted() {},
    methods:{

    }
}
</script>
