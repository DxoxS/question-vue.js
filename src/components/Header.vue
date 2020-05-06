<template>
    <div class="header">
        <input type="subｍit" @click="showText" value="受け取る">
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