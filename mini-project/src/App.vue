<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    
    <nav id="miniNav">

        <ul class="miniNav">
          
            <select class="currency">
              <option value="volvo">DKK</option>
              <option value="saab">EUR</option>
              <option value="opel">USD</option>
            </select>
            <li> <i class="fa fa-shopping-cart"></i> <a href="#">Cart</a></li>
            
            <li><router-link to="/signin">Sign In</router-link></li>
            <li><a href="#">Register</a></li>
        </ul>
    </nav>
    <nav id="mainNav">
        <router-link to="/"> <img src="./assets/img/logo.png" alt="logo"> </router-link>
        <ul class="mainNav">
            <li>
                <a href="#">Search bar</a>
            </li>
            <li>
                <a href="#">LOOK BOOK</a>
            </li>
            <li>
                <a href="#"> LOCAL STORES</a>
            </li>
            <li>
                <a href="#">THE BRAND</a>
            </li>
            <li>
                <a href="#">WOMENS</a>
            </li>
            <li>
                <a href="#">MENS</a>
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
            <h1>AWARD WINNER</h1>
            <p>FASHION AWARDS 2016</p>
        </div>
        <div class="social">
          <i class="fab fa-facebook-f"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-instagram"></i> 
          <i class="fab fa-pinterest"></i>
        </div>
        
    </footer>
    <footer class="bottomBar">
            <p class="copyright">© 2016 Avenue Fashion™</p>
            <p class="author">RobbyDesigns.com</p>
            <p class="site">Dev by Loremipsum.com™</p>
    </footer>
  </div>
</template>

<script>
</script>

<style lang="scss">
@import "./assets/scss/style.scss";
</style>
