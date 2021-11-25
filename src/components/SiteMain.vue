<template>
  <div class="main">
      <div class="container d-flex main_first">
          <div class="main_top_left">
              <p><strong class="strong">HAC TELLUS, FELIS RISUS AT </strong>mattis mattis. Eget euismod <br>semper eget tortor, donec amet, blandit. Tristique facilisi faucibus <br>elementum feugiat in nam in feugiat. Ipsum odio etiam duis <br>facilisis amet vulputate.
              </p>
              <h2>FOOD IS OUR COMMON <br>GROUND, A UNIVERSAL <br>EXPERIENCE.</h2>
              <p>Tristique tempus condimentum diam donec. Condimentum <br>ullamcorper sit elementum hendrerit mi nulla in consequat, ut. <br> Metus, nullam scelerisque netus viverra dui. </p>
              <img class="firma" src="../assets/images/signature-200x172.jpg" alt="">
          </div>
          <div class="main_top_right">
              <img src="../assets/images/info22x.jpg" alt="">
          </div>
      </div>
      <div class="container main_bottom">
          <div class="row ">
              <div class="col-4 text-center">
                  <img src="../assets/images/sushi-1.png" alt="">
                  <h5>THE BEST TABLE IN TOWN</h5>
                  <hr>
                  <p>Sed aenean egestas us aliquam turpis mauris, <br>molestie. Vitae tellus tempor sem id tempus <br>neque, tellus turpis turpis. Morbi tortor id <br>gravida aliquet. </p>
                  <button>EXPLORE THE MENU</button>
              </div>
              <div class="col-4 text-center">
                  <img src="../assets/images/sushi-2.png" alt="">
                  <h5>PERFECT FOR GROUPS</h5>
                  <hr>
                  <p>Quam eu proin sit massa condimentum. <br>Volutpat non pulvinar aliquet nunc. Orci <br>elementum in aliquet a gravida vivamus <br> aliquam turpis vitae</p>
                  <button>MAKE A RESERVATION</button>
              </div>
              <div class="col-4 text-center">
                  <img src="../assets/images/sushi-3.png" alt="">
                  <h5>FRESH PRODUCE EVERYDAY</h5>
                  <hr>
                  <p>Hendrerit amet, volutpat leo non, commodo <br>maecenas scelerisque tincidunt. Morbi <br>vulputate morbi purus quisque sit sagittis orci <br> elementum gravida.</p>
                  <button>LEARN MORE ABOUT US</button>
              </div>
          </div>
      </div>
      <div class="main_second d-flex row">
          <div class="col-7">
              <img class="img_main_second" src="../assets/images/slider32x.jpg" alt="">
          </div>
          <div class="col-5">
              <div class="d-flex text">
                  <div class="line"></div>
                  <div>
                      <p>FINE DINING EXPERIENCE</p>
                  </div>
              </div>
              <div class="dining">
                  <h1>THE BEST TABLE IN <br>TOWN</h1>
                  <p class="text-start">Pellentesque vitae viverra risus, sagittis. <br>Venenatis ridiculus scelerisque nisi in urna <br>nulla. Sit tempor a et nisl, ac felis.</p>
                  <button>EXPLORE THE MENU</button>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.main {
    height: 100%;
    .main_first {
        margin-top: 110px;
        .main_top_left {
            margin-left: 100px;
            margin-top: 60px;
          h2 {
            margin-top: 40px;
            font-weight: 700;
            margin-bottom: 40px;
          }
          .firma {
            margin-top: 20px;
          }
          p {
              color: #A5A6AE;
              .strong {
                  color: black;
              }
          }
        }
        .main_top_right {
          img {
              width: 476px;
              margin-left: 130px;
          }
        }
    }
    .main_bottom {
        width: 77%;
        margin-top: 140px;
        h5 {
            margin-top: 40px;
        }
        hr {
            width: 60px;
            margin-left: 145px;
            margin-top: 30px;
            margin-bottom: 30px;
        }
        p {
            color: #8d8d96;

        }
        button {
            background: white;
            border: 1px solid #A5A6AE;
            color: #52535c;
            font-size: 12px;
            width: 190px;
            height: 36px;
            margin-top: 17px;
            margin-bottom: 150px;
        }
    }
    .main_second {
        .img_main_second {
            width: 100%;
            height: 610px;
            object-fit: cover;
            object-position: top;
        }
        .col-7 {
            padding-right: 0px;
        }
        .col-5 {
            background: black;
            .text {
                margin-top: 150px;
                margin-left: 90px;
                .line {
                border-top: 1px solid #9BA59E;;
                width: 45px;
                margin-top: 8px;
                margin-right: 35px;
                }
                p {
                color: #9BA59E;
                font-size: 13px;
                }
            }
            .dining {
                h1 {
                    color: white;
                    margin-left: 170px;
                    margin-top: 15px;
                    line-height: 51px;
                }
                p {
                   color: #9BA59E;
                   margin-left: 170px;
                   margin-top: 40px;
                }
                button {
                    margin-left: 170px;
                    background: black;
                    color: white;
                    border: 1px solid white;
                    font-size: 13px;
                    width: 174px;
                    height: 36px;
                    margin-top: 40px;

                }
            }
        }
    }
    
}

</style>