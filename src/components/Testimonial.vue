<template>
  <div class="testimonials-zone">
            <img src="@/assets/classic-shop/images/man_testimonial.png" alt="">
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt amet molestias, facilis beatae aperiam rerum eaque commodi iusto consequatur eligendi ratione dignissimos, tempora quia porro veritatis tempore, unde nesciunt sapiente?</p>
            <h4>Darìo Pineda, Theme Fusion</h4>
            <div class="points">
                <div class="point"></div>
                <div class="point1"></div>
            </div>
        </div>
</template>

<script>
export default {
    name : `Testimonial`
}
</script>

<style scoped lang ="scss">
    .testimonials-zone {
        height: 550px;
        background-image: url("../assets/classic-shop/images/testimonials_home_1_bg.jpg");
        background-size: cover;
        background-position: center;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        color: white;
        p {
            width: 50%;
            line-height: 40px;
            font-size: 19px;
            text-align: center;
            margin: 20px;
        }
        .points {
            display: flex;
            align-items: center;
            justify-content: center;
            .point {
                height: 15px;
                width: 15px;
                background-color: white;
                margin: 50px 5px 0;
                border-radius: 50px;
                border: 1px solid white;
                cursor: pointer;
            }
            .point1 {
                height: 15px;
                width: 15px;
                background-color: rgba($color: #000000, $alpha: 0.1);
                margin: 50px 5px 0;
                border-radius: 50px;
                border: 1px solid white;
                cursor: pointer;
            }
        }
    }
</style>