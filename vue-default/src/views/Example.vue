<template>
   <div>
       <input type="text" v-model="lastName">
       <input type="text" v-model="firstName">
       <h1>Hello, {{getFullName()}}</h1>
       <h1>Hello, {{fullName}}</h1>
       <h1>Hello, {{lastName}}{{firstName}}</h1>
   </div>
</template>
<script>
export default {
    name:'',
    components:{},
    data(){
        return{
           firstName:'윤경',
           lastName:'오',

        };
    },
    computed:{
        fullName(){
            return this.lastName + this.firstName;
        }
    },
    setup() {},
    create() {},
    mounted() {}, 
    unmounted() {},
    methods:{
        getFullName(){
            return this.lastName + this.firstName;
        }
    }
}
</script>
