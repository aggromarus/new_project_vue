<template>
<!--  TODO: зарефакторить вот эту ерунду. Кода дофига, толку -нифига. -->
  <div class="footer">
    <div class="footer__background">
      <div class="container footer__wrap">
        <div class="footer__info">
          <img src="../assets/subs.png" alt="SUBSCRIBE"/>
          <p>
            “Vestibulum quis porttitor dui! Quisque viverra nunc mi, a
            pulvinar purus condimentum“
          </p>
        </div>
        <div class="footer__describe">
<!--          TODO: пофиксить всратую кнопку подписки с инпутом-->
          <p>SUBSCRIBE <br/>FOR OUR NEWLETTER AND PROMOTION</p>
          <br/>
          <br/>
          <input
              type="email"
              id="email"
              name="email"
              placeholder="Enter Your Email"
          />
          <a href="#" id="subscribe">Subscribe</a>
        </div>
      </div>
    </div>

    <div class="footer__bottom container">
      <span>2021 Brand All Rights Reserved.</span>
      <div class="links">
<!--        TODO: стили - добавить fontawesome, без него посыпались линки. Или вообще нахер его убрать.-->
        <a class="fab fa-facebook-square" href="https://www.facebook.com/">
        </a>
        <a class="fab fa-instagram" href="https://www.instagram.com/"></a>
        <a
            class="fab fa-pinterest-square"
            href="https://www.pinterest.ru/"
        ></a>
        <a class="fab fa-twitter-square" href="https://twitter.com/"></a>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Footer-Component-item'
}
</script>