<template>
<!--  TODO: пофиксить вывод картинок из массива-->
<!--  TODO: настроить роутинг, добавить вместо ссылки роут правильный-->
  <div class="card" v-for="item in list" :key="item.id">
    <a href="#"><img src="@/assets/images/1.png" alt=""></a>
    <div class="card__text">
      <h4>{{ list.label }}</h4>
      <p>{{ list.description }}</p>
      <div class="card__price">100500$</div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Product-Card-item',
  data() {
    return {
      list: [
        {
          id: 1,
          label: 'some text in label',
          description: 'lorem,lorem,lorem,lorem,lorem,lorem,',
          img: './images/1.png'
        },
        {
          id: 2,
          label: 'some text in label 2',
          description: 'lorem,lorem,lorem,lorem,lorem,lorem,2',
          img: 'src/assets/images/2.png'
        },
        {
          id: 3,
          label: 'some text in label 3',
          description: 'lorem,lorem,lorem,lorem,lorem,lorem,3',
          img: 'src/assets/images/3.png'
        },
        {
          id: 4,
          label: 'some text in label 4',
          description: 'lorem,lorem,lorem,lorem,lorem,lorem,4',
          img: 'src/assets/images/4.png'
        },
        {
          id: 5,
          label: 'some text in label 4',
          description: 'lorem,lorem,lorem,lorem,lorem,lorem,4',
          img: 'src/assets/images/4.png'
        },
        {
          id: 6,
          label: 'some text in label 4',
          description: 'lorem,lorem,lorem,lorem,lorem,lorem,4',
          img: 'src/assets/images/4.png'
        },
      ]
    }
  }
}
</script>