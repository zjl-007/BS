<template>
  <div class="home-content">
      <div class="home-content-header">
          <span class=".left"></span>
          <span class=".right"></span>
      </div>
  </div>
</template>
<script>
export default {
  name: "HomeBackground",
  props: {
    
  },
  data() {
    return {
      headerData: {
        name: "header",
      },
    };
  },
};
</script>
<style scoped>
.home-content {
  height: 100%;
}
.home-content-header {
  width: 100%;
  background-color: #80c342;
  height: 42px;
  position: relative;
}
.home-content-header .title {
  height: 42px;
  line-height: 42px;
}
</style>
