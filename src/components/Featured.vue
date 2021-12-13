<template>
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
                        <div class="filter">
                            <div class="check-box">
                                <i class="far fa-check-circle"></i>
                            </div>
                        </div>
                    </div>
                    <div class="name">Black Leather Jacket</div>
                    <div class="categories">Men, Jackets, Jeans</div>
                    <div><div class="firstPrice">$235</div><div class="price">$200</div></div>
                </div>
                <div class="second-model">
                    <div class="box-model">
                        <img src="@/assets/classic-shop/images/black_leather_suit-400x520.jpg" alt="">
                        <div class="filter">
                            <div class="check-box">
                                <i class="far fa-check-circle"></i>
                            </div>
                        </div>
                    </div>
                    <div class="name">Black Leather Suit</div>
                    <div class="categories">Men, Jackets</div>
                    <div><div class="price">176$</div></div>
                </div>
                <div class="third-model">
                    <div class="box-model">
                        <img src="@/assets/classic-shop/images/blue_jacket_and_white_stripe_tee-400x520.jpg" alt="">
                        <div class="filter">
                            <div class="check-box">
                                <i class="far fa-check-circle"></i>
                            </div>
                        </div>
                    </div>
                    <div class="name">Blue Jacket & Stripe Tee</div>
                    <div class="categories">Men, Jackets, Suits</div>
                    <div><div class="price">$580</div></div>
                </div>
                <div class="fourth-model">
                    <div class="box-model">
                        <img src="@/assets/classic-shop/images/modern_black_leather_suit-400x520.jpg" alt="">
                        <div class="filter">
                            <div class="check-box">
                                <i class="far fa-check-circle"></i>
                            </div>
                        </div>
                    </div>
                    <div class="name">Modern Black Leather Suit</div>
                    <div class="categories">Men, Jackets</div>
                    <div><div class="price">$96</div></div>
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name : `Featured`,
}
</script>

<style scoped lang = "scss">
    .featured {
        width: 1200px;
        margin: 150px auto;
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
        .men-models {
        display: flex;
        width: 1200px;

        .first-model {
            padding: 10px;
            width: calc(100% / 4);
        }
        .second-model {
            padding: 10px;
            width: calc(100% / 4);
        }
        .third-model {
            padding: 10px;
            width: calc(100% / 4);
        }
        .fourth-model {
            padding: 10px;
            width: calc(100% / 4);
        }
        .box-model {
            width: 100%;
            cursor: pointer;
            position: relative;
             &:hover .filter {
                display: flex;
            }
            img {
                width: 100%;
            }
            .filter {
                position: absolute;
                width: 100%;
                height: 100%;
                top: 0%;
                left: 0%;
                justify-content: center;
                align-items: center;
                background: rgb(81,136,213);
                background: linear-gradient(180deg, rgba(81,136,213,1) 2%, rgba(81,136,213,0.75) 41%, rgba(240,166,210,0.75) 59%, rgba(240,166,210,1) 98%);
                display: none;
                .check-box {
                    width: 70px;
                    height: 70px;
                    border-radius: 50%;
                    background-color: #201d29;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    opacity: 1.0;
                    i {
                        color: white;
                        font-size: 30px;
                    }
                }
            }
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
    }
</style>