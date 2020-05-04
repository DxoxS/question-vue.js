<template>
  <div class="home">
    <div class="people_box">
      <p :style="vStyle">{{people.boy}}</p>
      <p>{{people.girl}}</p>
    </div>
  </div>
</template>
<script>
  export default{
    data(){
      return{
        people:{
          boy:"男の子",
          girl:"女の子"
        },
        vStyle: {color:"bule"}
      }
    }
  }
</script>
<style scoped>

</style>