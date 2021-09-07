<template>
    <div>
        <!-- <img v-bind:src="url" alt=""> -->
        <input type="text" v-model="textValue">
        <button type="button" v-bind:disabled="textValue==''">Click</button>
    </div>
</template>
<script>
export default {
    name:'',
    components:{},
    data(){
        return{
            url:"https://img.khan.co.kr/news/2006/12/07/6l07k11a.webp",
            textValue:''
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
