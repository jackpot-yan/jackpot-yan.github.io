<template>
  <div id="home">
    <div id="homeLift">
      <el-avatar :size="250" src="@/assets/logo.png" />
    </div>
    <div id="homeCount">这里还没有想好</div>
  </div>
</template>
<script setup></script>
<style scoped>
#home {
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 100%;
}
#homeLift {
  width: 40%;
  height: 100%;
  display: flex;
}
#homeCount {
  width: 60%;
  height: 100%;
  background-color: red;
}
</style>
