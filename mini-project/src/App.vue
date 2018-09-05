<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <nav id="miniNav">

        <ul class="miniNav">
            <li> <a href="#">Curency - dropdown</a> </li>
            <li><a href="#">Register</a></li>
            <li><a href="#">Sign In</a></li>
            <li><a href="#">Cart - dropdown</a></li>
        </ul>
    </nav>
    <nav id="mainNav">
        <a href="#"> <img src="img/logo.png" alt="#"> </a>
        <ul class="mainNav">
            <li>
                <a href="#">MENS - dropdown</a>
            </li>
            <li>
                <a href="#">WOMENS - dropdown</a>
            </li>
            <li>
                <a href="#">THE BRAND</a>
            </li>
            <li>
                <a href="#"> LOCAL STORES - dropdown</a>
            </li>
            <li>
                <a href="#">LOOK BOOK - dropdown </a>
            </li>
            <li>
                <a href="#">Search bar</a>
            </li>
        </ul>

    </nav>
    <router-view/>
    <footer>
        <div class="footerLinks">
            <ul>
                <h5>INFORMATION</h5>
                <li class="item1"> <a href="#"> The brand </a> </li>
                <li class="item1"> <a href="#"> Local stores </a> </li>
                <li class="item1"> <a href="#"> Customer serivce </a> </li>
                <li class="item1"> <a href="#"> Privacy &amp; cookies</a> </li>
                <li class="item1"> <a href="#"> Site map </a> </li>
            </ul>
            <ul>
                <h5>WHY BUY FROM US</h5>
                <li class="item1"> <a href="#"> Shipping &amp; returns</a> </li>
                <li class="item1"> <a href="#"> Secure shopping </a> </li>
                <li class="item1"> <a href="#"> Testimonials </a> </li>
                <li class="item1"> <a href="#"> Award winning </a> </li>
                <li class="item1"> <a href="#"> Ethical trading </a> </li>
            </ul>
            <ul>
                <h5>YOUR ACCOUNT</h5>
                <li class="item1"> <a href="#"> Sign in </a> </li>
                <li class="item1"> <a href="#"> Register </a> </li>
                <li class="item1"> <a href="#"> View cart </a> </li>
                <li class="item1"> <a href="#"> View your lookbook </a> </li>
                <li class="item1"> <a href="#"> Track an order </a> </li>
                <li class="item1"> <a href="#"> Update information </a> </li>
            </ul>
            <ul>
                <h5>LOOKBOOK</h5>
                <li class="item1"> <a href="#"> Latest posts </a> </li>
                <li class="item1"> <a href="#"> Men's lookbook </a> </li>
                <li class="item1"> <a href="#"> Women's lookbook </a> </li>
                <li class="item1"> <a href="#"> Lookbook RSS feed </a> </li>
                <li class="item1"> <a href="#"> View your lookbook </a> </li>
                <li class="item1"> <a href="#"> Delete your lookbook </a> </li>
            </ul>
            <ul>
                <h5>CONTACT DETAILS</h5>
                <li class="item1"> <a href="#"> Head Office: Avenue Fashion, <br> 180-182 Regent Street, London. </a> </li>
                <li class="item1"> <a href="#"> Telephone: 0123-456-789 </a> </li>
                <li class="item1"> <a href="#"> Email: support@yourwebsite.com </a> </li>

            </ul>
        </div>
        <div class="award">
            <!-- Skift ud med content -->
            <img src="img/award.png" alt="">
        </div>
        <div class="social">
            <img src="img/social.png" alt="">
        </div>
        <div class="bottomBar">
            <p class="copyright">© 2016 Avenue Fashion™</p>
            <p class="author">RobbyDesigns.com</p>
            <p class="site">Dev by Loremipsum.com™</p>
        </div>
    </footer>
  </div>
</template>

<style lang="scss">
@import "./assets/scss/style.scss";
</style>
