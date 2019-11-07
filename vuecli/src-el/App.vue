<template>
<div id="app">
  <Layout></Layout>
</div>
</template>

<script>
  import Layout from './layout';

  export default {
      data(){
          return{}
      }
      ,components:{
          Layout
      }
  }

</script>

<style>
  *{
    margin: 0;
    padding: 0;
  }
  html,body,#app{
    height: 100%;
  }
</style>
