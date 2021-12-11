<template>
  <div class="footer">
    <div class="container">
        <div class="reference">
          <div class="logo">
              <img src="@/assets/classic-shop/images/classic_shop_logo_footer.png" alt="">
          </div>

          <div class="adress">
              <div>12345 North Main Street</div>
              <div>New York, NY 555555</div>
              <div>Phone: 1.800.555.6789</div>
              <div>Email: info@company.com</div>
              <div>Web: Theme-fusion.con</div>
          </div>

          <div class="social">
            <i class="fab fa-facebook-f"></i>
            <i class="fab fa-twitter"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-youtube"></i>
          </div>

        </div>
        <div class="top-rated">
            <span>TOP RATED</span>
                <div class="feed">
                    <div class="feed-text">
                        <span>Leather Gloves</span>
                        <div class="star">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <div class="price">
                            <strong>$45</strong>
                        </div>
                    </div>
                    <div class="feed-img">
                        <img src="@/assets/classic-shop/images/leather_gloves-400x520.jpg" alt="">
                    </div>
                </div>
                <hr size = "1">
                <div class="feed">
                    <div class="feed-text">
                        <span>Black Leather Jacket</span>
                        <div class="star">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <div class="price">
                            <strong class="first-price">$235</strong>
                            <strong class="second-price">$125</strong>
                        </div>
                    </div>
                    <div class="feed-img">
                        <img src="@/assets/classic-shop/images/black_elegant_leather_jacket.jpg" alt="">
                    </div>
                </div>
                <hr size = "1">
                <div class="feed">
                    <div class="feed-text">
                        <span>Spring Printed Dress</span>
                        <div class="star">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <div class="price">
                            <strong>$47</strong>
                        </div>
                    </div>
                    <div class="feed-img">
                        <img src="@/assets/classic-shop/images/spring_printed_dress-400x520.jpg" alt="">
                    </div>
                </div>
                <hr size = "1">
        </div>
        <div class="recent-post">

        </div>
        <div class="tags">

        </div>
    </div>
      
  </div>
</template>

<script>
export default {
    name : `Footer`,
}
</script>

<style scoped lang = "scss">
  .footer {
    background-color: #2b2e32;
    .container {
      width: 1200px;
      margin: auto;
      display: flex;
      padding: 50px 0;
      .reference {
        width: 25%;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        .logo {
          width: 50%;
          img {
            width: 100%;
          }
        }
        .adress {
          color: #dbdcdc;
        }
        .social {
          color: #dbdcdc;
          i {
            margin: 10px;
            font-size: 18px;
          }
        }
      }
      .top-rated {
        color: #dbdcdc;
        width: 25%;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        .feed {
          margin: 10px 0;
          width: 100%;
          display: flex;
          justify-content: space-between;
          .feed-text {
            display: flex;
            flex-direction: column;
            .star {
              color: #427ed1;
              margin: 10px 0;
            }
            .price {
              width: 50%;
              display: flex;
              justify-content: space-between;
              .first-price {
                text-decoration: line-through;
              }
              .second-price {
                text-decoration: underline;
              }
            }
          }
          .feed-img {
            width: 70px;
            cursor: pointer;
            img {
            width: 100%;
            }
          }
        }
      }
      .recent-post {
        width: 25%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
      }
      .tags {
        width: 25%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
      }
    }
  }
</style>