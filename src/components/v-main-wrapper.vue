<template>
<div class ="v-main-wrapper">
    <p>{{title}} </p>

</div>

</template>

<script>
export default {
    name: "v-main-wrapper",
    components:{
    },
    props :{

    },
    data(){
        return {
            title : "Main Wrapper"
        }
    },
    coputed:{

    },
    methods:{

    },
    watch:{

    },
    mounted(){

    }
}
</script>

<style>
.v-main-wrapper{
    display:flex;
    justify-content: center;
    align-items: center;
    max-width: 900px;
    margin:0 auto;

}


</style>