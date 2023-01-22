<template>
  <div id="right-panel"></div>
</template>

<script>
export default {};
</script>

<style scoped>
#left-panel {
  width: 100%;
  height: 30%;
  background-color: yellow;
}

@media only screen and (min-width: 720px) {
  #left-panel {
    width: 50vw;
    height: 100%;
  }
}
</style>
