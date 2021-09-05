<template>
    <div>
        <div v-html="htmlString"> </div>
        <input type="text">
    </div>
    
</template>
<script>
export default {
    name:'',
    components:{},
    data(){
        return{
            htmlString:'<p style="color:red;">This is a red string.</p>',
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
