<template>
  <div class="home">
    <input v-model="getText" type="text" >
    <Header :parentText="getText"></Header>
  </div>
</template>

<script>
import Header from
'../components/Header'
export default{
  data(){
    return{
      getText:'',
    }
  },
  components:{
    Header
  }
}
</script>


