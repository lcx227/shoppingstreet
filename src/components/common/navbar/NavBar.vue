<template>
  <div class="nav-bar">
    <div class="left">
      <slot name="left"></slot>
    </div>
    <div class="center">
      <slot name="center"></slot>
    </div>
    <div class="right">
      <slot name="right"></slot>
    </div>
  </div>
</template>

<script>
  export default{

  }
</script>

<style  lang='css'>
  .nav-bar{
    position: fixed;
    z-index: 100;
    display: flex;
    width: 100%;
    height: 44px;
    line-height: 44px;
    box-shadow: 0 1px 1px rgba(100, 100, 100, .2);
  }
  .left,.right{
    width: 60px;
  }
  .center{
    flex: 1;
    text-align: center;
  }
</style>