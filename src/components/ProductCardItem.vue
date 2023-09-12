<template>
  <div class="card">
    <a href="#"
    ><img src="@/assets/beard_man.png" alt="beard_man"
    /></a>
    <div class="card__text">
      <h4>ELLERY X M'O CAPSULE</h4>
      <p>
        Known for her sculptural takes on traditional tailoring,
        Australian arbiter of cool Kym Ellery teams up with Moda
        Operandi.
      </p>
      <div class="card__price">100500$</div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Product-Card-item',
  props: {
    list: {
      type: Array,
      required: true
    }
  }
}
</script>