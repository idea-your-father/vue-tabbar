<template>
  <div id="tab-bar">

    <slot></slot>
    <!-- 使用 slot 插槽，动态插入子元素s -->
  </div>

</template>

<script>
    export default {
        name: "TabBar"
    }
</script>

<style scoped>




  #tab-bar{
    display: flex;
    background-color: #f6f6f6;
    position: fixed;
    right: 0;
    left: 0;
    bottom: 0;
    box-shadow: 0 -1px 1px rgba(100,100,100,.1);

  }


</style>
