<script>
export default {
  props: {
    list: {
      type: Array,
      required: true
    }
  }
}

</script>

<template>
<div> <strong> Поле1 </strong>{{list.id}}</div>
<div> <strong> Поле2 </strong>{{list.label}}</div>
<div> <strong> Поле3 </strong>{{list.img}}</div>
<div> <strong> Поле4 </strong>{{list.price}}</div>
</template>

<style scoped>

</style>