<template>
  <div class="navbar__right navbar__right__hover">
    <a class="navbar__right__lang navbar-hover">
      <img class="navbar__right__lang__img" src="../../assets/us-flag.png" />
    </a>
    <a class="navbar__right__acc navbar-hover">
      <span class="navbar__right__acc--top">Hello, Sign in</span>
      <span class="navbar__right__acc--bot">Account & Lists</span>
    </a>
    <a class="navbar__right__orders navbar-hover">
      <span class="navbar__right__orders--top">Returns</span>
      <span class="navbar__right__orders--bot">& Orders</span>
    </a>
    <a class="navbar__right__cart navbar-hover">
      <span class="navbar__right__cart__icon">
        <span class="navbar__right__cart__icon--number">0</span>
        <img
          class="navbar__right__cart__icon--img"
          src="../../assets/cart.png"
        />
      </span>
      <span class="navbar__right__cart__text">Cart</span>
    </a>
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
    width: 70px;
    display: flex;
    align-content: center;
    &__img {
      margin: 27px 15px 16px 15px;
    }
  }
  &__acc {
    width: 120px;
    display: flex;
    flex-direction: column;
    padding: 15px 0;
    &--top {
      font-size: 12px;
    }
    &--bot {
      font-size: 14px;
      font-weight: 600;
    }
  }
  &__orders {
    width: 80px;
    display: flex;
    flex-direction: column;
    padding: 15px 0;
    &--top {
      font-size: 12px;
    }
    &--bot {
      font-size: 14px;
      font-weight: 600;
    }
  }
  &__cart {
    width: 90px;
    padding: 12px 0;
    display: flex;
    flex-direction: row;
    &__icon {
      &--number {
        position: absolute;
        margin: 0px 20px 0px 20px;
        color: #f08804;
        font-weight: 600;
      }
      &--img {
        margin: 5px 0;
        position: relative;
      }
    }
    &__text {
      margin: 17px 0 0 0;
      font-weight: 800;
      font-size: 14px;
    }
  }
}
</style>
