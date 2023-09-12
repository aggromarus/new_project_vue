<script>
import TestComponentVue from "@/components/TestComponentVue.vue";

export default {
  components: {TestComponentVue},
  data(){
    return {
      list : [
        {id: 1, label: 'some text', img: 'some image', price: 300},
        {id: 2, label: 'some text', img: 'some image', price: 300},
        {id: 3, label: 'some text', img: 'some image', price: 300},
        {id: 4, label: 'some text', img: 'some image', price: 300},
        {id: 5, label: 'some text', img: 'some image', price: 300},
      ],
    }
  },
}
</script>

<template>
<test-component-vue :list="list"/>
</template>

<style scoped>

</style>