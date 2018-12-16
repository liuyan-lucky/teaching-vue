<template>
  <div id="app">
    <div class="dell" @click="handleClick">{{message}}</div>
    <!--<img src="./assets/logo.png">-->
    <!--<router-view/>-->
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      message:"hello"
    }
  },
  methods:{
    handleClick(){
      this.message="bye"
    }
  }
}
</script>

<style scoped>
.dell{
  color:red;
}
</style>
