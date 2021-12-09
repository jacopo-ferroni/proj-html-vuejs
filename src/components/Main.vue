<template>
  <div class="main">
    <div class="new-arrivals">
        <div class="arrivals-text">
            <h1>
                Brand New Arrivals
            </h1>
            <span>NEW COLLECTION FROM NEW YORK</span>
            <div class="button-section">
                <div class="button">
                    VIEW ALL
                </div>
                <div class="button">
                    LOOKBOOK
                </div>
            </div>
        </div>

        <div class="banner">
            <div class="demos">
                <i class="fas fa-tags"></i>
                <div>Demos</div>
            </div>
            <div class="sale">
                <div class="price">39</div>
                <div>On Sale</div>
                <i class="fas fa-dollar-sign"></i>
            </div>
        </div>
    </div>
    <div class="featured">
        <div class="titleFeatured">
            <hr size="1">
            <h1>Featured Products</h1>
            <hr size="1">
        </div>
        <span>Must have products from our top sellers</span>
        <div class="category-selection">
            <div class="men">
                Men
            </div>
            <div class="women">
                Women
            </div>
            <div class="accessories">
                Accesories
            </div>
        </div>
        <div class="men-models">
            <div class="first-model">
                <div class="box-model">
                    <img src="@/assets/classic-shop/images/black_elegant_leather_jacket-400x520.jpg" alt="">
                </div>
                <div class="name">Black Leather Jacket</div>
                <div class="categories">Men, Jackets, Jeans</div>
                <div><div class="firstPrice">$235</div><div class="price">$200</div></div>
            </div>
            <div class="second-model">
                <div class="box-model">
                    <img src="@/assets/classic-shop/images/black_leather_suit-400x520.jpg" alt="">
                </div>
                <div class="name">Black Leather Suit</div>
                <div class="categories">Men, Jackets</div>
                <div><div class="price">176$</div></div>
            </div>
            <div class="third-model">
                <div class="box-model">
                    <img src="@/assets/classic-shop/images/blue_jacket_and_white_stripe_tee-400x520.jpg" alt="">
                </div>
                <div class="name">Blue Jacket & Stripe Tee</div>
                <div class="categories">Men, Jackets, Suits</div>
                <div><div class="price">$580</div></div>
            </div>
            <div class="fourth-model">
                <div class="box-model">
                    <img src="@/assets/classic-shop/images/modern_black_leather_suit-400x520.jpg" alt="">
                </div>
                <div class="name">Modern Black Leather Suit</div>
                <div class="categories">Men, Jackets</div>
                <div><div class="price">$96</div></div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name : `Main`,
}
</script>

<style scoped lang = "scss">
    .new-arrivals {
        height: 650px;
        background-image: url("../assets/classic-shop/images/home1_slide_three_bg_2.jpg");
        background-size: cover;
        background-position-y: center;
        display: flex;
        align-items: center;
        justify-content: center;
        position: relative;
        .arrivals-text {
            width: 50%;
            height: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            color: white;
            h1 {
                font-size: 100px;
            }
            span {
                font-size: 30px;
                padding: 25px 0;
            }
            .button-section {
                display: flex;
                align-items: center;
                justify-content: center;
                .button {
                    border: 3px solid white;
                    padding: 20px 40px;
                    border-radius: 25px;
                    background-color: rgba($color: white, $alpha: 0.1);
                    margin: 10px;
                    cursor: pointer;
                    &:hover {
                        transition: 2s;
                        background-color: white;
                        color: black;
                    }
                }
            }
        }
        .banner {
            position: absolute;
            top: -10px;
            right: 15px;
            z-index: 1;
            .demos {
                box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.6);
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                background-color: white;
                height: 60px;
                margin-bottom: 5px;
                border-radius: 5px;
                color: gray;
                cursor: pointer;
                i {
                    font-size: 30px;
                }
                div {
                    font-size: 13px;
                }
            }
            .sale {
                box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.6);
                background-color: white;
                position: relative;
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                border-radius: 5px;
                height: 60px;
                padding: 10px;
                color: gray;
                cursor: pointer;
                .price {
                    font-size: 30px;
                    color: #6cbf81;
                }
                div {
                    font-size: 13px;
                }
                
                i {
                    position: absolute;
                    top: 5px;
                    left: 5px;
                    color: #6cbf81;
                }
            }
        }

    }
    .featured {
        width: 1200px;
        margin: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        .titleFeatured {
            display: flex;
            align-items: center;
            width: 100%;
            justify-content: space-between;
            font-size: 20px;
            color: #2b2e32;
            margin-bottom: 20px;
            hr {
                width: 30%;
                color: gray;
            }
        }
        span {
            color: #2b2e32;
            font-size: 17px;
        }
        .category-selection {
            display: flex;
            border: 1px solid #b6b3b3;
            margin-top: 60px;
            .men {
                padding: 15px 60px;
                cursor: pointer;
                background-color: #f6f6f6;
                &:active {
                    background-color: white;
                }
            }
            .women {
                cursor: pointer;
                padding: 15px 60px;
                border-left: 1px solid #b6b3b3;
                border-right: 1px solid #b6b3b3;
                background-color: #f6f6f6;
                &:active {
                    background-color: white;
                }
            }
            .accessories {
                cursor: pointer;
                padding: 15px 60px;
                background-color: #f6f6f6;
                &:active {
                    background-color: white;
                }
            }
        }
    }
    .men-models {
        margin: 50px 0 150px 0;
        display: flex;
        width: 1200px;

        .first-model {
            width: calc(100% / 4);
        }
        .second-model {
            width: calc(100% / 4);
        }
        .third-model {
            width: calc(100% / 4);
        }
        .fourth-model {
            width: calc(100% / 4);
        }
        .box-model {
            width: 100%;
            img {
                width: 100%;
            }
            cursor: pointer;
        }
        .name {
            margin: 10px 0;
            cursor: pointer;
        }
        .categories {
            font-size: 13px;
            color: gray;
            cursor: pointer;
        }
        .firstPrice {
            text-decoration: line-through;
            color: #427ed5;
            display: inline-block;
            margin: 10px 10px 10px 0;
            font-size: 14px;
        }
        .price {
            color: #427ed5;
            display: inline-block;
            margin: 10px 10px 10px 0;
            cursor: pointer;
        }
    }

</style>