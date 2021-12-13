<template>
  <div class="headerFirst">
      <div class="container">
          <div class="brands">
              <i class="fab fa-facebook-f"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-instagram"></i>
              <i class="fab fa-youtube"></i>
          </div>

          <div class="functionButton">
              <div class="shoppingCart">
                  Shopping Cart
              </div>
              <div class="myAccount">
                  My Account
                  <i class="fas fa-chevron-down"></i>
              </div>
              <div class="cart">
                  <i class="fas fa-shopping-cart"></i>
                  CART
                  <i class="fas fa-chevron-down"></i>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name : `Header1`,
}
</script>

<style scoped lang="scss">
    .headerFirst {
        position: fixed;
        z-index: 3;
        width: 100%;
        background-color: white;
        border-top: 3px solid #427ed5;
        border-bottom: 2px solid #f6f6f6;
        height: 55px;
        .container {
            width: 1200px;
            height: 100%;
            margin: auto;
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 100%;
            .brands {
                color: #575c61;
                padding: 10px;
                i {
                    margin: 0 7px;
                    padding: 3px;
                    cursor: pointer;
                }
            }
            .functionButton {
                height: 100%;
                width: 40%;
                display: flex;
                align-items: center;
                justify-content: space-between;
                .shoppingCart {
                    width: 30%;
                    height: 100%;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    font-size: 13px;
                    cursor: pointer;
                    color: grey;
                }
                .myAccount {
                    width: 30%;
                    height: 100%;
                    border-left: 2px solid #f6f6f6;
                    border-right: 2px solid #f6f6f6;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    font-size: 13px;
                    cursor: pointer;
                    color: grey;
                    i {
                        margin-left: 5px;
                    }
                }
                .cart {
                    width: 40%;
                    height: 100%;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    font-size: 13px;
                    cursor: pointer;
                    color: grey;
                    &:hover {
                        background: #f6f6f6;
                    }
                    i {
                        padding: 0 10px;
                    }
                }
            }
        }
    }
</style>