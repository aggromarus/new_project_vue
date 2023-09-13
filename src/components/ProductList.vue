<script>
import {defineComponent} from "vue";
import ProductCardItem from "@/components/ProductCardItem.vue";

export default defineComponent({
  components: {ProductCardItem}
})
</script>

<template>
  <div class="product product__wrap container">
    <ProductCardItem/>
  </div>
  <div class="link">
<!--    TODO: пофиксить кнопку, стили к ней. А то тут херня какая-то написана-->
    <a class="link__browse" href="#">Browse All Product</a>
  </div>
</template>

<style scoped>

</style>