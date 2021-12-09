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
    }

</style>