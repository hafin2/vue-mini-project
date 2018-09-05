<template>
  <div class="home">
<div class="hero">
        <img src="../assets/img/hero.png" alt="">
    </div>

    <div class="tabs">
        <hr>
        <ul>
            <li><a href="#">POPULAR</a></li>
            <li><a href="#">NEW ARRIVALS</a></li>
            <li><a href="#">BEST SELLERS</a></li>
            <li><a href="#">SPECIAL OFFERS</a></li>
            <li><a href="#">COMMING SOON</a></li>
        </ul>
    </div>


    <div class="products">
        <div class="item1 product">
            <img src="../assets/img/item1.png" alt="">
        </div>
        <div class="item2 product">
            <img src="../assets/img/item2.png" alt="">
        </div>
        <div class="item3 product">
            <img src="../assets/img/item3.png" alt="">
        </div>
        <div class="item4 product">
            <img src="../assets/img/item4.png" alt="">
        </div>
        <div class="item5 product">
            <img src="../assets/img/item5.png" alt="">
        </div>
        <div class="item6 product">
            <img src="../assets/img/item6.png" alt="">
        </div>
        <hr>
    </div>

    <div class="lookBook">
        <div class="mens">
            <img src="../assets/img/lookBook.png" alt="">
            <h2>MEN'S</h2>
            <H2>LOOKBOOK</H2>
            <P> Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam natus perspiciatis aliquam obcaecati dolor quis sint rerum.</P>
            <button>VIEW NOW</button>
        </div>
        <div class="womens">
            <img src="../assets/img/lookBook.png" alt="">
        </div>
        <div class="your">
            <img src="../assets/img/lookBook.png" alt="">
        </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
