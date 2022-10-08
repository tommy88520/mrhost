<template>
  <div class="scroll-icon" v-scroll-to="options">
    <el-icon><Top /></el-icon>
  </div>
</template>

<script>
export default {
  name: 'ScrollTop',
  data () {
    return { 
      options: { element: '#header', easing: 'linear' }
    }
  }
}
</script>

<style lang="scss">
.scroll-icon {
  position: fixed;
  bottom: 30px;
  right: 5%;
  border-radius: 50%;
  border: 1px solid;
  width: 32px;
  height: 32px;
  cursor: pointer;
  background-color: #fff;
  i { 
    font-size: 30px;
  }
}
</style>
