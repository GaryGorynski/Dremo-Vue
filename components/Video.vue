<template>
  <div class="video">
    <div class="videoBox">
      <img class="videoBox__img" src="/assets/widelo.png" alt="novideo" />
      <svg class="videoBox__play"></svg>
      <svg class="videoBox__dot"></svg>
      <svg class="videoBox__triangle"></svg>
      <svg class="videoBox__triangleMini"></svg>
      <svg class="videBox__rectangle"></svg>
      <svg class="videBox__rectangle2"></svg>
      <svg class="videBox__rectangle3"></svg>
      <i class="videoBox__volume fas fa-volume-up"></i>
      <i class="videoBox__settings fas fa-cog"></i>
      <i class="videoBox__window fas fa-expand"></i>
      <hr class="videoBox__line" />
      <hr class="videoBox__line2" />
      <p class="videoBox__txt">1:01/6.21</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Video",
};
</script>

<style>
.video {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 1200px;
}
.videoBox {
  position: relative;
  bottom: 2050px;
  align-items: center;
  justify-content: center;
}
.videoBox__img {
  position: absolute;
  top: 1550px;
  left: 100px;
  border-radius: 5px 5px 0px 0px;
}

.videoBox__play {
  position: absolute;
  width: 1034px;
  height: 78px;
  left: 212px;
  top: 4120px;

  background: rgba(22, 18, 18, 0.6);
  backdrop-filter: blur(8px);
  z-index: 1;
  font-size: 2;
  top: 2008px;
  left: 100px;
}
.videoBox__dot {
  height: 75px;
  width: 75px;
  background: #4270c9;
  display: inline-block;
  border-radius: 50%;
  position: absolute;
  top: 1747px;
  left: 575px;
}
.videoBox__triangle {
  position: absolute;
  width: 0;
  height: 0;
  border-top: 15px solid transparent;
  border-left: 25px solid white;
  border-bottom: 15px solid transparent;
  top: 1772px;
  left: 604px;
}
.videoBox__triangleMini {
  position: absolute;
  width: 0;
  height: 0;
  border-top: 7px solid transparent;
  border-left: 12.5px solid white;
  border-bottom: 7px solid transparent;
  top: 2041px;
  left: 180px;
  z-index: 1;
}

.videBox__rectangle {
  width: 4px;
  height: 14px;
  background-color: white;
  position: absolute;
  top: 2041px;
  left: 140px;
  z-index: 1;
}
.videBox__rectangle2 {
  width: 4px;
  height: 14px;
  background-color: white;
  position: absolute;
  top: 2041px;
  left: 147px;
  z-index: 1;
}
.videBox__rectangle3 {
  width: 4px;
  height: 14px;
  background-color: white;
  position: absolute;
  top: 2041px;
  left: 192px;
  z-index: 1;
}
.videoBox__volume {
  position: absolute;
  font-size: 20px;
  top: 2038px;
  left: 237px;
  z-index: 1;
  color: white;
}
.videoBox__settings {
  position: absolute;
  font-size: 24px;
  top: 2036px;
  left: 1010px;
  z-index: 1;
  color: white;
}
.videoBox__window {
  position: absolute;
  font-size: 25px;
  top: 2035px;
  left: 1066px;
  z-index: 1;
  color: white;
}
.videoBox__line {
  border-top: 3px solid rgba(255, 255, 255, 0.5);
  border-bottom: 3px solid rgba(255, 255, 255, 0.5);
  width: 500px;
  position: absolute;
  top: 2037px;
  z-index: 1;
  left: 470px;
  border-radius: 5px;
  background-color: rgba(255, 255, 255, 0.5);
}
.videoBox__line2 {
  border-top: 3px solid #4270c9;
  border-bottom: 3px solid#4270C9;
  width: 200px;
  position: absolute;
  top: 2037px;
  z-index: 1;
  left: 350px;
  border-radius: 5px;
  background-color: rgba(255, 255, 255, 0.5);
}
.videoBox__txt {
  position: relative;
  top: 2030px;
  left: 278px;
  width: 50px;
  font-size: 12px;
  z-index: 1;
  color: white;
  font-family: roboto;
  font-weight: lighter;
}
</style>
