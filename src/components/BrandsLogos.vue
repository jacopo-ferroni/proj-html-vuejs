<template>
  <div class="brandLogos-zone">
            <div class="container">
                <span>BRAND LOGOS</span>
                <div class="logos">
                    <img src="@/assets/classic-shop/images/b_logotype_6.png" alt="">
                    <img src="@/assets/classic-shop/images/b_logotype_7.png" alt="">
                    <img src="@/assets/classic-shop/images/b_logotype_1.png" alt="">
                    <img src="@/assets/classic-shop/images/b_logotype_2.png" alt="">
                    <img src="@/assets/classic-shop/images/b_logotype_3.png" alt="">
                </div> 
            </div>
        </div>
</template>

<script>
export default {
    name : `BrandsLogos`
}
</script>

<style scoped lang = "scss">
    .brandLogos-zone {
        background-color: #f6f6f6;
        .container {
            padding: 50px 0;
            margin: auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 1200px;
            span {
                color: gray;
            }
            .logos {
                margin-top: 30px;
                width: 100%;
                display: flex;
                justify-content: space-between;
            }
        }
    }
</style>