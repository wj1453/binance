<template>
  <div id="app">
    <mt-header :title="pageTitle">
      <mt-button icon="more" slot="right"></mt-button>
    </mt-header>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
  data:function(){
    return {
      'pageTitle':'首页'
    }
  }
}
</script>

<style>
body{margin:0;padding:0;}
</style>
