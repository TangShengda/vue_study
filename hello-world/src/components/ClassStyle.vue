<template>
  <div class="wrap" :class="{ active: isActive }">
    <button @click="handleClick">切换颜色</button>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      isActive: true,
    };
  },
  methods: {
    handleClick: function () {
      this.isActive = !this.isActive
    },
  },
};
</script>
  
<style>
.wrap {
  width: 300px;
  height: 300px;
  background-color: pink;
}
.active {
  background-color: orange;
}
</style>