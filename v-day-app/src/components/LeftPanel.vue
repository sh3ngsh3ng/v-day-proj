<template>
  <div id="left-panel"></div>
</template>

<script>
export default {};
</script>

<style scoped>
#left-panel {
  width: 100%;
  height: 70%;
  background-color: green;
}

@media only screen and (min-width: 720px) {
  #left-panel {
    width: 50vw;
    height: 100%;
  }
}
</style>
