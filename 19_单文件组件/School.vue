<template>
    <div class="demo">
        <h2>学校名称：{{name}}</h2>
        <h2>学校地址：{{address}}</h2>
        <button @click="showName">点我提示学校名称</button>
    </div>
</template>

<script>
    export default {
        name:'School',
        data(){
            return{
                name:'zafu',
                address:'hangzhou'
            }
        },
        methods: {
            showName(){
                console.log(this.name);
            }
        },
    }
</script>
    
<style>
    .demo{
        background: orange;
    }
</style>