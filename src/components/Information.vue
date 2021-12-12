<template>
  <div class="information">
            <div class="info-box-1">
                <h1>70% Off</h1>
                <p>Vivamus tempor leo lacus, feugiat un magna aliquam erat.</p>
                <div class="button-view-more">
                    VIEW MORE
                </div>
            </div>
            <div class="info-box-2">
                <h1>Free Shipping</h1>
                <p>Vivamus tempor leo lacus, feugiat un magna aliquam erat.</p>
                <div class="button-view-more">
                    VIEW MORE
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name : `Information`
}
</script>

<style scoped lang = "scss">
    .information {
        height: 550px;
        background-image: url("../assets/classic-shop/images/bkgd_confetti-compressor.jpg");
        background-size: cover;
        background-position: center;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        .info-box-1 {
            background-image: url(../assets/classic-shop/images/promo_box_1_bg.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            height: 70%;
            width: 30%;
            margin: 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 0 0 0 50px;
        }
        .info-box-2 {
            background-image: url(../assets/classic-shop/images/promo_box_2_bg.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            height: 70%;
            width: 30%;
            margin: 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 0 0 0 50px;
        }
        .button-view-more {
            text-align: center;
            width: 30%;
            background-color: rgba($color: #ffffff, $alpha: 0.1);
            padding: 10px;
            border: 3px solid white;
            border-radius: 50px;
            font-size: 13px;
            cursor: pointer;
        }
        p {
            width: 45%;
            padding: 30px 0;
            line-height: 30px;
            font-size: 14px;
        }
        h1 {
            font-size: 40px;
        }
    }
</style>