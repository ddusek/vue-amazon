<template>
  <div class="navbar__left">
    <a class="navbar__left__logo navbar-hover" href="/">
      <img src="../../assets/logo.png" />
    </a>
    <a href="#" class="navbar__left__delivery navbar-hover">
      <img
        src="../../assets/location.png"
        class="navbar__left__delivery__location"
      />
      <span class="navbar__left__delivery__text">
        <span class="navbar__left__delivery__text--light">Deliver to</span>
        <span class="navbar__left__delivery__text--bold">Czech Republic</span>
      </span>
    </a>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.navbar__left {
  display: flex;
  align-items: center;
  height: 100%;
  &__logo {
    padding: 10px 20px 0 17px;
  }

  &__delivery {
    display: flex;

    &__location {
      height: 17px;
      width: 16px;
      padding-top: 10px;
      padding-right: 2px;
    }

    &__text {
      display: flex;
      flex-direction: column;
      width: 120px;
      &--light {
        font-size: 12px;
        color: rgb(205, 205, 205);
      }
      &--bold {
        font-size: 14px;
        font-weight: 700;
        color: white;
      }
    }
  }
}
</style>
