<template>
  <div class="header">
      <div class="container">
          <div class="brand">
              <img src="@/assets/classic-shop/images/classic_shop_logo2x.png" alt="">
          </div>

          <div class="button-selection">
                <div class = "selection">
                    Home
                    <i class="fas fa-chevron-down"></i>
                </div>
                <div class = "selection">
                    Shop
                    <i class="fas fa-chevron-down"></i>
                </div>
                <div class = "selection">
                    Products
                    <i class="fas fa-chevron-down"></i>
                </div>
                <div class = "selection">
                    Categories
                    <i class="fas fa-chevron-down"></i>
                </div>
                <div class = "selection">
                    News
                    <i class="fas fa-chevron-down"></i>
                </div>
                <div class = "selection">
                    Elements
                    <i class="fas fa-chevron-down"></i>
                </div>

                <div class="shop-now">
                    <strong>SHOP NOW!</strong>
                </div>

                <div class="search">
                    <i class="fas fa-search"></i>
                </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name : `Header`,
}
</script>

<style scoped lang = "scss">
.header {
    height: 100px;
    .container {
        width: 1200px;
        height: 100%;
        margin: auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
        .brand {
            height: 100%;
            display: flex;
            align-items: center;
            img {
                cursor: pointer;
                width: 60%;
            }
        }
        .button-selection {
            display: flex;
            align-items: center;
            height: 100%;
            .selection {
                cursor: pointer;
                padding: 0 20px;
                font-size: 15px;
                color: gray;
                height: 100%;
                display: flex;
                align-items: center;
                border-top: 4px solid white;
                &:hover {
                border-top: 4px solid #427ed5;
                color: #427ed5;
                }
                i {
                    padding: 0 0 0 5px;
                    font-size: 10px;
                }
            }
            .shop-now {
                cursor: pointer;
                color: white;
                background-color: #427ed5;
                padding: 15px 30px;
                border-radius: 25px;
                font-size: 13px;
            }
            .search {
                cursor: pointer;
                padding: 0 0 0 30px;
            }
        }
    }
}
</style>