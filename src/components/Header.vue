<template>
    <div class="header">
        <input type="subnit" @click="showText" placeholder="受け取る">
        <p>{{show}}</p>
    </div>
</template>
<script>
export default {
    data(){
        return{
            show:''
        }
    },
    props:["parentText"],
    methods:{
        showText(){
            this.show = this.parentText
        }
    }
}
</script>
<style scoped>
    
</style>