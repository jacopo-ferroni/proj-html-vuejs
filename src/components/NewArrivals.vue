<template>
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
</template>

<script>
export default {
    name : `NewArrivals`,
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
</style>    