<template>
  <div class="mod-home">
    <h3>林场一张图</h3>
    在common/home.vue文件中引入GIS地图
    <a v-bind:href="url">http://172.16.4.21/WEBMAPCONTROL/MapTest.htm</a> 
  </div>
</template>

<script>
  export default {
  }
</script>

<style>
  .mod-home {
    line-height: 1.5;
  }
</style>

