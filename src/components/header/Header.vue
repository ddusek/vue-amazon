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

<style lang="scss">
.navbar {
  display: flex;
  background-color: rgb(25, 25, 25);
  color: white;
  height: 60px;
}
.navbar-hover {
  border: 1px solid transparent;
  cursor: pointer;
  &:hover {
    border: #ffffff solid 1px;
  }
}
</style>
