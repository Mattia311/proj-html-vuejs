<template>
  <div class="footer">
    <div class="image">
      <img src="../assets/images/footer2x.jpg" alt="">
    </div>
    <div class="text_footer text-center">
      <img src="../assets/images/logo-restaurant-2x.png" alt="">
      <p>Quam eu proin sit massa condimentum. Volutpat non pulvinar <br>aliquet nunc. Quam eu proin sit massa condimentum.</p>
      <i class="fab fa-facebook-f"></i>
      <i class="fab fa-twitter"></i>
      <i class="fab fa-youtube"></i>
      <i class="fab fa-instagram"></i>
      <i class="fab fa-linkedin-in"></i>
    </div>
    <div class="copy text-center">
      <p>Copyright 2012 - 2019 Avada | All Rights Reserved | Powered by WordPress | ThemeFusion</p>
    </div>
    <div class="arrow_top">
      <div>
        <i class="fas fa-chevron-up"></i>
      </div>
      <div class="block">

      </div>
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.footer {
  position: relative;
  .image {
   img {
    width: 1443px;
    z-index: 0;
   }
  }
  .text_footer {
    position: absolute;
    top: 0;
    margin-left: 480px;
    margin-top: 150px;
    img {
      width: 250px;
      margin-bottom: 60px;
     
    }
    p {
      color: white;
      
    }
    i {
      background: white;
      width: 40px;
      height: 40px;
      border-radius: 25px;
      padding-top: 12px;
      margin-right: 9px;
      margin-top: 30px;
    }
  }
  .copy {
    background: #5c3d27;
    color: white;
    height: 40px;
    font-size: 10px;
    padding-top: 13px;
  }
  .arrow_top {
    
    padding-top: 30px;
    i {
      background: gray;
      width: 40px;
      height: 40px;
      padding-left: 12px;
      padding-top: 12px;
      position: fixed;
      bottom: 30px;
      margin-left: 1200px;
    }
    .block {
      width: 100%;
      height: 30px;
      background:#5c3d27 ;
      position: fixed;
      bottom: 0;
    }
  }

}


</style>