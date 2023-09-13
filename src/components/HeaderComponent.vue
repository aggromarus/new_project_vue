<script>
export default {
  name: "Header-component"
}
</script>

<template>
  <div class="header">
    <div class="header__wrap container">
      <div class="header__left">
<!--        TODO: я бы переделал хедер. Уж больно тупо как то left & right-->
        <a href="index.html"><img src="@/assets/logo.png" alt="logo"/></a>
        <img src="@/assets/search.png" alt="search"/>
      </div>
      <div class="header__right">
        <img src="@/assets/burger.png" alt="burger__menu"/>
        <a href="#"><img src="@/assets/account.png" alt="account"/></a>
        <a href="#"><img src="@/assets/buy.png" alt="buy"/></a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.header {
  background-color: #222222;
  color: aliceblue;
  padding: 19px 0;

  &__wrap {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  &__left {
    & img {
      text-decoration: none;
      margin-right: 41px;
    }
  }

  &__right {
    & img {
      &:not(:last-child) {
        margin-right: 33px;
      }
    }
  }
}
</style>