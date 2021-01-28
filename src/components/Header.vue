<template>
  <div class="navbar">
    <div class="navbar__left">
      <span class="navbar__left__logo">
        <a href="/">
          <img src="../assets/logo.png" />
        </a>
      </span>
      <a href="#" class="navbar__left__delivery">
        <img src="../assets/location.png" class="navbar__left__delivery__location" />
        <span class="navbar__left__delivery__text">
          <span class="navbar__left__delivery__text--light">Deliver to</span>
          <span class="navbar__left__delivery__text--bold">Czech Republic</span>
        </span>
      </a>
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
    a, a:hover, a:focus, a:active {
    text-decoration: none;
    color: inherit;
  }
  &__left {
    width: 20%;
    display: flex;
    align-items: center;
    
    &__logo {
      margin: 10px 20px 0 17px;

    }

    &__delivery {
      display: flex;
      
      &__location {
        height: 20px;
        width: 18px;
        margin-top: 5px;
        padding-right: 2px;
      }

      &__text {
        display: flex;
        flex-direction: column;

        &--light {
          font-size: 12px;
          color: rgb(205, 205, 205)
        }
        &--bold {
          font-size: 14px;
          font-weight: 700;
          color: white;
        }
      }
    }
  }

  &__mid {
    width: 40%;
  }

  &__right {
    width: 40%;
  }
}
</style>
