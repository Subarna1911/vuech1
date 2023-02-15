<template>
  <div class="container">
    <HeaderTag title="Task Tracker"/>


  </div>
  
</template>

<script>
import HeaderTag from './components/Header.vue'

export default{
  name:'App',
  components:{
    HeaderTag,

  },
}




</script>

<style>
*{
  box-sizing: border-box;
  margin: 0%;
  padding: 0px;
}
.container{
  border: 2px solid rgb(123, 74, 74);
  height: 50vh;
  width: 50vw;
  margin-top: 23px;
  margin-left: 34px;
}


</style>
