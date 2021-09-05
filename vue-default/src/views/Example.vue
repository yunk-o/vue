<template>
    <div>
        <input type="text" v-model="valueModel"/>
        <p>{{valueModel}}</p>
        <input type="number" v-model.number="valueModel2"> <br>
        <textarea v-model="valueModel3">gg</textarea>
        <div>{{valueModel3}}</div>
    </div>
</template>
<script>
export default {
    name:'',
    components:{},
    data(){
        return{
            valueModel:'South Korea',
            valueModel2:12,
            valueModel3:"안녕하세요"
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
