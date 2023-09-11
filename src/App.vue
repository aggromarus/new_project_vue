<script setup>
import Header from "@/components/Header.vue";
import ProductCardItem from "@/components/ProductCardItem.vue";
import ProsItemCard from "@/components/ProsItemCard.vue";
import FooterComponentItem from "@/components/FooterComponentItem.vue";
</script>

<template>
  <body>
  <Header/>
  <main>
    <section class="promo">
      <div class="promo__wrap container">
        <div class="promo__title">
          <h1>THE BRAND</h1>
          <p>OF LUXERIOUS <span>FASHION</span></p>
        </div>
      </div>
    </section>

    <section class="category"> ////////////////// заменить на  компонент category__item
      <div class="category__wrap container">
        <div class="category__item">
          <p>30% OFF <br/><span> FOR WOMEN</span></p>
        </div>
        <div class="category__item">
          <p>HOT DEAL <br/><span> FOR MEN</span></p>
        </div>
        <div class="category__item">
          <p>NEW ARRIVALS <br/><span> FOR KIDS</span></p>
        </div>
        <div class="category__item">
          <p>LUXIROUS & TRENDY <br/><span>ACCESORIES</span></p>
        </div>
      </div>
    </section>
    <div class="featured">
      <h3>Fetured Items</h3>
      <p>Shop for items based on what we featured in this week</p>
      <!-- указать переменные для <p> -->
    </div>
    <section class="product">
      <div class="container">
        <div class="product__wrap">
          <Product-Card-item/>
          <Product-Card-item/>
          <Product-Card-item/>
          <Product-Card-item/>
          <Product-Card-item/>
          <Product-Card-item/>
        </div>
      </div>
    </section>
    <div class="link"> пофиксить кнопку эту вот
      <a class="link__browse" href="#"
      >Browse All Product</a
      >
    </div>
  </main>

  <div class="comfort">
    <div class="footer__wrap container"> // поменять значения в компонентах, передать правильные пропсы
      <Pros-item-card/>
      <Pros-item-card/>
      <Pros-item-card/>
    </div>
  </div>
  <Footer-Component-item/>
  </body>
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
