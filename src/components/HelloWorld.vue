<template>
  <baidu-map class="bm-view" ak="p5oRGm1aWZVnmdubKGGp5mdtp8XS6KHz">

  </baidu-map>
</template>
<script>
  import BaiduMap from 'vue-baidu-map/components/map/Map.vue'
  export default {
    components:{
      BaiduMap
    }
  }
</script>
<style scoped>
  .bm-view{
    width:100%;
    height: 300px;
  }
</style>
