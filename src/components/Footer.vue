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
            <span class="toprated-title">TOP RATED PRODUCTS</span>
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
          <div class="title-recent">
            RECENT POSTS
          </div>
          <div class="line">
            <i class="fas fa-chevron-right"></i>
            <div>Aenean lobortis sapien enim viverra</div>
          </div>
          <hr size="1">
          <div class="line">
            <i class="fas fa-chevron-right"></i>
            <div>Duis ac massa semper maximus</div>
          </div>
          <hr size="1">
          <div class="line">
            <i class="fas fa-chevron-right"></i>
            <div>Nunc fermit nulla eu justo sem id</div>
          </div>
          <hr size="1">
          <div class="line">
            <i class="fas fa-chevron-right"></i>
            <div>Aliquam posuere magna eget nibh</div>
          </div>
          <hr size="1">
          <div class="line">
            <i class="fas fa-chevron-right"></i>
            <div>Cras ac nulla ac consecte rutrum</div>
          </div>
          <hr size="1">
          <div class="line">
            <i class="fas fa-chevron-right"></i>
            <div>Fusce mattis nunc ut aliquam</div>
          </div>
          <hr size="1">
        </div>
        <div class="tags">
          <div class="title-tag">
            TAGS
          </div>
          <div class="tags-container">
            <div class="tag">Black</div>
            <div class="tag">boots</div>
            <div class="tag">Brown</div>
            <div class="tag">Casual</div>
            <div class="tag">D&G</div>
            <div class="tag">Fabric</div>
            <div class="tag">flowers</div>
            <div class="tag">Grey</div>
            <div class="tag">Hat</div>
            <div class="tag">Hipster</div>
            <div class="tag">lines</div>
            <div class="tag">multi-purpose</div>
            <div class="tag">New York</div>
            <div class="tag">Outdoors</div>
            <div class="tag">red</div>
            <div class="tag">responsive</div>
            <div class="tag">summer</div>
            <div class="tag">sweater</div>
            <div class="tag">Travel</div>
            <div class="tag">Warm</div>
            <div class="tag">White</div>
            <div class="tag">winter</div>
          </div>
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
        margin: 10px;
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
        margin: 10px;
        color: #dbdcdc;
        width: 25%;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        .toprated-title {
          margin-bottom: 30px;
        }
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
        margin: 10px;
        width: 25%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        .title-recent {
          color: #dbdcdc;
          margin-bottom: 30px;
        }
        .line {
          display: flex;
          align-items: center;
          justify-content: flex-start;
          color: #dbdcdc;
          cursor: pointer;
          i {
            margin-right: 10px;
            font-size: 13px;
          }
        }
      }
      .tags {
        margin: 10px;
        width: 25%;
        display: flex;
        flex-direction: column;
        .title-tag {
          color:#dbdcdc;
          margin-bottom: 30px;
        }
          .tags-container {
            display: flex;
            flex-wrap: wrap;
            .tag {
              border: 1px solid rgba($color: #dbdcdc, $alpha: .1);
              padding: 5px 10px;
              color: #dbdcdc;
              margin: 2px;
              cursor: pointer;
              &:hover {
                border: 1px solid rgba($color: #dbdcdc, $alpha: .5);
              }
            }
          }
      }
    }
  }
</style>