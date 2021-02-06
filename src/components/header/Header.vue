<template>
  <div class="navbar">
    <HeaderLeft />
    <HeaderFill />
    <HeaderRight />
  </div>
</template>

<script>
import HeaderLeft from "./HeaderLeft.vue";
import HeaderFill from "./HeaderFill.vue";
import HeaderRight from "./HeaderRight.vue";
export default {
  name: "App",
  components: {
    HeaderLeft,
    HeaderFill,
    HeaderRight
  }
};
</script>

<style lang="scss" scoped>
.navbar {
  display: flex;
  background-color: rgb(25, 25, 25);
  color: white;
  height: 60px;
}
</style>
