<template>
  <div class="header d-flex">
      <div class="header_left">
          <div class="header_left_top">
              <img class="img_header_left" src="../assets/images/logo-restaurant-2x.png" alt="">
          </div>
          <div class="header_left_bottom">
              <div class="d-flex text">
                  <div class="line"></div>
                  <div>
                      <p>THE BEST TABLE IN TOWN</p>
                  </div>
              </div>
              <div class="dining">
                  <h1>FINE DINING <br>EXPERIENCE</h1>
                  <p class="text-start">Pellentesque vitae viverra risus, sagittis. <br>Venenatis ridiculus scelerisque nisi in urna <br>nulla. Sit tempor a et nisl, ac felis.</p>
                  <button>EXPLORE THE MENU</button>
              </div>
          </div>
      </div>
      <div class="header_right">
          <img class="img_header" src="../assets/images/slider52x.jpg" alt="">
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.header {
    .header_left {
        background: black;
        height: 800px;
        width: 600px;
        .img_header_left {
            margin-left: 60px;
            width: 250px;
            margin-top: 30px;
        }
        .header_left_bottom {
            .text {
                margin-top: 150px;
                margin-left: 69px;
                .line {
                border-top: 1px solid #9BA59E;;
                width: 35px;
                margin-top: 8px;
                margin-right: 40px;
                }
                p {
                color: #9BA59E;
                font-size: 13px;
                }
            }
            .dining {
                h1 {
                    color: white;
                    margin-left: 140px;
                    margin-top: 15px;
                    line-height: 51px;
                }
                p {
                   color: #9BA59E;
                   margin-left: 140px;
                   margin-top: 40px;
                }
                button {
                    margin-left: 140px;
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
    .header_right {
        .img_header {
            width: 840px;
            height: 800px;
           
        }
    }
}

</style>