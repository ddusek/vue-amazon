<template>
  <div class="navbar__fill">
    <form class="navbar__fill__form" action="/" method="get">
      <select
        id="category"
        class="navbar__fill__form__dropdown"
        name="category"
      >
        <option v-for="category in categories" v-bind:key="category.key">
          <span>{{ category.value }}</span>
        </option>
      </select>
      <span class="navbar__fill__form__container">
        <input
          id="searchInput"
          class="navbar__fill__form__container__textbox"
          type="text"
          name="searchInput"
        />
      </span>
      <span class="navbar__fill__form__search">
        <input
          id="submit"
          class="navbar__fill__form__search__button"
          type="submit"
          value="search"
          name="submit"
        />
      </span>
    </form>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      categories: [
        { key: 1, value: "All" },
        { key: 2, value: "Arts & Crafts" },
        { key: 3, value: "Automotive" },
        { key: 4, value: "Baby" },
        { key: 5, value: "Beauty & Personal Care" },
        { key: 6, value: "Books" }
      ]
    };
  }
};
</script>

<style lang="scss">
textarea,
.navbar__fill {
  width: 100%;
  display: flex;
  margin: 12px 5px;
  &__form {
    display: flex;
    width: 100%;
    &__dropdown {
      height: 100%;
      width: auto;
      border: 0;
      border-radius: 5px 0 0 5px;
    }
    &__container {
      min-width: 200px;
      height: 100%;
      width: 100%;
      &__textbox {
        flex: 1;
        height: 100%;
        border: none;
        padding: 0;
        width: 100%;
      }
    }

    &__search {
      background: url("../../assets/search.png");
      &__button {
        height: 100%;
        border: 0;
        border-radius: 0 5px 5px 0;
        background-color: #febd69;
      }
      margin-left: auto;
    }
  }
}
</style>
