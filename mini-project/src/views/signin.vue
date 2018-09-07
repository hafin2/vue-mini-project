<template>
  <div class="signin">
    <div class="signin-hero">
        <img src="../assets/img/signin.png" alt="">
    </div>


<div class="signin-container">
    <div class="signin-form">
      <h3>SIGN IN</h3>
      <input type="email" name="email" id="email" placeholder="Your Email..">
      <input type="password" name="password" id="password" placeholder="Your Password..">
      <button>SIGN IN</button>
    </div>

<!-- <div class="vl"></div> -->

    <div class="signup-form">
      <h3>REGISTER</h3>
      <input type="email" name="email" id="signup-email" placeholder="Your Email..">
      <input type="password" name="signup-password" id="signup-password" placeholder="Your Password..">
      <input type="password" name="signup-password2" id="signup-password2" placeholder="Confirm Password..">



      <label class="label-container"> <p>Sign up for exclusive updates, discounts, new arrivals, contests, and more!</p> 
        <input type="checkbox">
        <span class="checkmark"></span>
      </label>

    <div class="btn-policy">
      <button>CREATE ACCOUNT</button>
      <p align="right" class="policy">By clicking ‘Create Account’, you <br> agree to our Privacy Policy <i class="fas fa-long-arrow-alt-right"></i></p>
      </div>
    </div>

  </div>
</div>
</template>

<script>
export default {
  name: "signin"
};
</script>

<style>
#mainNav {
  position: initial;
}
</style>
