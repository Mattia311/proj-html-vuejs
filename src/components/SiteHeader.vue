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
          <div>
              <img class="img_header" src="../assets/images/slider52x.jpg" alt="">
          </div>
          <div>
              <SiteMenu/>
          </div>
          <div class="fixed">
              <div class="fixed_top text-center">
                  <img src="../assets/images/svgexport-3.svg" alt="">
                  <p>Demos</p>
              </div>
              <div class="fixed_bottom">
                  <div class="d-flex text-center">
                      <p class="prezzo1">$</p>
                      <p class="prezzo2">39</p>
                  </div>
                  <div class="text-center">
                      <p>On sale</p>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
import SiteMenu from './SiteMenu.vue';

export default {
    components: {
    SiteMenu
  }

}
</script>

<style lang="scss">
.header {
    .header_left {
        background: #5c3d27;
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
                    background: #5c3d27;
                    color: white;
                    border: 1px solid white;
                    font-size: 13px;
                    width: 174px;
                    height: 36px;
                    margin-top: 40px;

                }
                button:hover {
                    background: white;
                    color: #5c3d27;
                }
            }
        }
        
    }
    .header_right {
        .img_header {
            width: 840px;
            height: 800px;
            position: relative;
        }
        ul {
            position: absolute;
            top: 30px;
            margin-left: 45px;
            li {
            list-style: none;
            margin-right: 35px;
            }
            a {
                text-decoration: none;
                color: white;
                font-size: 14px;
            }
            button {
                background: transparent;
                color: white;
                border: 1px solid white;
            }
        
        }
        .fixed {
            position: absolute;
            top: 130px;
            right: 1.5%;
            position: fixed;
            z-index: 1;
            .fixed_top {
                background: white;
                border-radius: 10px;
                width: 70px;
                box-shadow:  2px  2px 2px rgb(143, 137, 137),
                             -2px -2px 2px rgb(143, 137, 137),
                             2px -2px 2px rgb(143, 137, 137),
                             -2px  2px 2px rgb(143, 137, 137);
                
            }
            .fixed_bottom {
                background: white;
                width: 70px;
                border-radius: 10px;
                box-shadow:  2px  2px 2px rgb(143, 137, 137),
                             -2px -2px 2px rgb(143, 137, 137),
                             2px -2px 2px rgb(143, 137, 137),
                             -2px  2px 2px rgb(143, 137, 137);
                .prezzo1 {
                    color: yellowgreen;
                    margin-left: 10px;
                    margin-bottom: 0%;
                }
                .prezzo2 {
                    color: yellowgreen;
                    font-size: 26px;
                    margin-bottom: 0%;
                }
                
            }
        }
    }
}

</style>