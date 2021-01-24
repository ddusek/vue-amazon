<template>
  <div class="navbar">
    <div class="navbar__left">
      logo, deliver to
    </div>
    <div class="navbar__mid">
      find product
    </div>
    <div class="navbar__right">
      language, cart, etc
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
.navbar {
  display: flex;
  background-color: rgb(25, 25, 25);
  color: white;
  height: 60px;

  &__left {
    width: 20%;
  }

  &__mid {
    width: 40%;
  }

  &__right {
    width: 40%;
  }
}
</style>
