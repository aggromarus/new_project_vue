<script setup>
import ProsItemCard from "@/components/ProsItemCard.vue";
import FooterComponentItem from "@/components/FooterComponentItem.vue";
import ProductList from "@/components/ProductList.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
</script>

<template>
  <div>
  <HeaderComponent/>

  <main>
    <section class="promo">
      <div class="promo__wrap container">
        <div class="promo__title">
          <h1>THE BRAND</h1>
          <p>OF LUXERIOUS <span>FASHION</span></p>
        </div>
      </div>
    </section>

    <section class="category">
<!--      TODO: заменить на компонент category__item-->
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
    <ProductList/>
  </main>

  <div class="comfort">
    <div class="footer__wrap container">
<!--TODO: поменять значения в компонентах, передать правильные пропсы-->
      <Pros-item-card/>
      <Pros-item-card/>
      <Pros-item-card/>
    </div>
  </div>

  <Footer-Component-item/>

  </div>
</template>

<style scoped>
</style>
