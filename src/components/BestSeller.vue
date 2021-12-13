<template>
  <div class="best-seller-zone">
            <div class="titleBestseller">
                <hr size="1">
                <h1>Best Seller</h1>
                <hr size="1">
            </div>
            <span>Must have products from our top sellers</span>
            <div class="carousel">
                <div class="button-left">
                    <i class="fas fa-chevron-left"></i>
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/spring_printed_dress-400x520.jpg" alt="">
                    <div class="filter">
                        <div class="object-title">
                            <h1>Flowers Tee</h1>
                            <div>Women, t-Shirt</div>
                            <div class="price">$68</div>
                        </div>

                        <div class="object-btn">
                            <div class="cart">
                                <i class="fas fa-shopping-cart"></i>
                                <div>Add to cart</div>
                            </div>

                            <div class="details">
                                <i class="fas fa-list-ul"></i>
                                <div>Details</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/modern_love_tee-400x520.jpg" alt="">
                    <div class="filter">
                        <div class="object-title">
                            <h1>Love Tee</h1>
                            <div>Women, t-Shirt</div>
                            <div class="price">$99</div>
                        </div>

                        <div class="object-btn">
                            <div class="cart">
                                <i class="fas fa-shopping-cart"></i>
                                <div>Add to cart</div>
                            </div>

                            <div class="details">
                                <i class="fas fa-list-ul"></i>
                                <div>Details</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/black_leather_jacket-400x520.jpg" alt="">
                    <div class="filter">
                        <div class="object-title">
                            <h1>Leather Woman Jacket</h1>
                            <div>Women, Leather Jacket</div>
                            <div class="price">$150</div>
                        </div>

                        <div class="object-btn">
                            <div class="cart">
                                <i class="fas fa-shopping-cart"></i>
                                <div>Add to cart</div>
                            </div>

                            <div class="details">
                                <i class="fas fa-list-ul"></i>
                                <div>Details</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/black_elegant_leather_jacket.jpg" alt="">
                    <div class="filter">
                        <div class="object-title">
                            <h1>Leather Man Jacket</h1>
                            <div>Man, Leather Jacket</div>
                            <div class="price">$250</div>
                        </div>

                        <div class="object-btn">
                            <div class="cart">
                                <i class="fas fa-shopping-cart"></i>
                                <div>Add to cart</div>
                            </div>

                            <div class="details">
                                <i class="fas fa-list-ul"></i>
                                <div>Details</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/hipster_black_top-400x520.jpg" alt="">
                    <div class="filter">
                        <div class="object-title">
                            <h1>Short Tee</h1>
                            <div>Women, t-Shirt</div>
                            <div class="price">$39</div>
                        </div>

                        <div class="object-btn">
                            <div class="cart">
                                <i class="fas fa-shopping-cart"></i>
                                <div>Add to cart</div>
                            </div>

                            <div class="details">
                                <i class="fas fa-list-ul"></i>
                                <div>Details</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="button-right">
                    <i class="fas fa-chevron-right"></i>
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name : `BestSeller`
}
</script>

<style scoped lang = "scss">
    .best-seller-zone {
        width: 1200px;
        margin: 150px auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        .titleBestseller {
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
        .carousel {
            padding: 30px 0 0 0;
            display: flex;
            align-items: center;
            width: 100%;
            .button-left {
                width: 2%;
                display: flex;
                justify-content: center;
                align-items: center;
                padding: 25px 15px;
                background-color: #c1c1c1;
                cursor: pointer;
            }
            .button-right {
                width: 2%;
                display: flex;
                justify-content: center;
                align-items: center;
                padding: 25px 15px;
                background-color: #c1c1c1;
                cursor: pointer;
            }
            .model-box {
                cursor: pointer;
                width: calc(96% / 5);
                position: relative;
                img {
                    width: 100%;
                }
                &:hover .filter {
                    display: flex;
                }
                .filter {
                    position: absolute;
                    width: 100%;
                    height: 100%;
                    top: 0%;
                    left: 0%;
                    flex-direction: column;
                    justify-content: flex-end;
                    align-items: center;
                    background: rgb(81,136,213);
                    background: linear-gradient(180deg, rgba(81,136,213,1) 2%, rgba(81,136,213,0.75) 41%, rgba(240,166,210,0.75) 59%, rgba(240,166,210,1) 98%);
                    display: none;
                    .object-title {
                        text-align: center;
                        color: white;
                        display: flex;
                        flex-direction: column;
                        justify-content: center;
                        align-items: center;
                        margin-bottom: 50px;
                    }
                    .object-btn {
                        width: 100%;
                        display: flex;
                        justify-content: space-between;
                        padding: 20px;
                        .cart {
                            font-size: 13px;
                            color: white;
                            display: flex;
                            i {
                                margin-right: 5px;
                            }
                        }
                        .details {
                            font-size: 13px;
                            color: white;
                            display: flex;
                            i {
                                margin-right: 5px;
                            }
                        }
                    }
                }
            }
        }
    }
</style>