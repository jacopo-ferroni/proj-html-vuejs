<template>
    <div class="new-arrivals-zone">
            <div class="titlenew-arrivals-zone">
                <hr size="1">
                <h1>New Arrivals</h1>
                <hr size="1">
            </div>
            <span>Brand new products from top designer</span>
            <div class="carousel">
                <div class="button-left">
                    <i class="fas fa-chevron-left"></i>
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/black_elegant_leather_jacket.jpg" alt="">
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/hipster_black_top-400x520.jpg" alt="">
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/black_leather_suit-400x520.jpg" alt="">
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/spring_printed_dress-400x520.jpg" alt="">
                </div>
                <div class="model-box">
                    <img src="@/assets/classic-shop/images/modern_love_tee-400x520.jpg" alt="">
                </div>
                <div class="button-right">
                    <i class="fas fa-chevron-right"></i>
                </div>
            </div>
    </div>
</template>

<script>
export default {
    name : `NewArrivals2`
}
</script>

<style scoped lang = "scss">
    .new-arrivals-zone {
        padding: 150px 0;
        display: flex;
        flex-direction: column;
        align-items: center;
        .titlenew-arrivals-zone {
            display: flex;
            align-items: center;
            width: 80%;
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
            padding: 100px 0 0 0;
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
                img {
                    width: 100%;
                }
            }
        }
    }
</style>