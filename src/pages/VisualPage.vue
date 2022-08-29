<template>
  <div class="canvas" style="opacity: .2">
    <iframe src="../../public/static/Background.html" :style="{width: width, height:height}" frameborder="0" ></iframe>
  </div>
  <div class="head">
    <h1>战伤救治全程生命体征实时监测与智能预警系统</h1>
  </div>
  <div class="mainbox">
    <div class="clearfix">
      <div class="item">
        <div class="boxall" style="height: 20.4rem">
          <div class="alltitle">官兵人员信息</div>
          <div class="allnav" id="echart1"></div>
          <div class="boxfoot"></div>
        </div>
        <div class="boxall" style="height: 20.4rem">
          <div class="alltitle">医护人员信息</div>
          <div class="allnav" id="echart2"></div>
          <div class="boxfoot"></div>
        </div>
      </div>
      <div class="item">
        <div style="height: 60px; width:100%;"></div>
        <div class="map">
          <div class="map1"><img src="../assets/lbx.png"></div>
          <div class="map2"><img src="../assets/jt.png"></div>
          <div class="map3"><img src="../assets/map.png"></div>
          <div class="map4" id="map_1"></div>
        </div>
      </div>
      <div class="item">
        <div class="boxall" style="height:20.4rem">
          <div class="alltitle">病区人员处理情况</div>
          <div class="allnav" id="echart4"></div>
          <div class="boxfoot"></div>
        </div>
        <div class="boxall" style="height:20.4rem">
          <div class="alltitle">伤员密度预测</div>
          <div class="allnav" id="echart5"></div>
          <div class="boxfoot"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "../css/visual.css"
export default {
  // name: "VisualPage",
  setup() {
    return {
      //自适应窗口高度
      height: window.innerHeight + 'px',
      width: '100%'
    }
  }
};
</script>

<style scoped>

</style>
