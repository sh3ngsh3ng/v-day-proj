<template>
  <div id="mainpage-div">
    <LeftPanel />
    <div id="right">Right Panel</div>
  </div>
</template>

<script>
import LeftPanel from "./LeftPanel.vue";
export default {
  name: "MainPage",
  components: {
    LeftPanel,
  },
};
</script>

<style scoped>
#mainpage-div {
  display: flex;
  flex-wrap: wrap;
  width: 100vw;
  height: 100vh;
}

#right {
  width: 100%;
  height: 30%;
  background-color: yellow;
}

@media only screen and (min-width: 720px) {
  #left {
    width: 50vw;
    height: 100%;
  }
  #right {
    width: 50vw;
    height: 100%;
  }
}
</style>
