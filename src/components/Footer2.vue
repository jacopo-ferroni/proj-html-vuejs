<template>
    <div class="footer2">
        <div class="footer-text">
            ©Copyright 2012 - 2021 | Avada Theme by Theme Fusion | All Rights Reserved | Powered By JacopoFerroniPress
        </div>
        <img src="@/assets/classic-shop/images/payment_cards_footer.png" alt="">
    </div>
</template>

<script>
export default {
    name : `Footer2`,
}
</script>

<style scoped lang="scss">
    .footer2 {
        padding: 50px 0;
        background-color: #1d1f22;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        .footer-text {
            margin-bottom: 20px;
            color: #dbdcdc;
        }
    }
</style>