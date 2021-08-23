<template>
  <div class="navbar__right">
    <span class="navbar__right__lang">
      <img class="navbar__right__lang__img" src="../../assets/us-flag.png" />
    </span>
    <span class="navbar__right__acc">sign in</span>
    <span class="navbar__right__orders">orders</span>
    <span class="navbar__right__cart">cart</span>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.navbar__right {
  width: 600px;
  height: 100%;
  display: flex;

  &__lang {
    width: 100px;
    display: flex;
    align-content: center;
    &__img {
      margin: 20px 20px;
    }
  }
}
</style>
