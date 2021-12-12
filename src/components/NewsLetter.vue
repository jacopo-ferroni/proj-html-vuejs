<template>
  <div class="newsletter-zone">
            <div class="container">
                <div class="newsletter-text">
                    <div class="email-icon">
                        <i class="far fa-envelope"></i>
                    </div>

                    <h1>Subscribe now and get special offers</h1>

                </div>
                <div class="send-email">
                    <input type="email" placeholder="insert your email">

                    <!-- tasto send -->
                    <div class="send">
                        SEND
                    </div>
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name : `NewsLetter`
}
</script>

<style scoped lang = "scss">
    .newsletter-zone {
        background-color: #303337;
        display: flex;
        align-items: center;
        .container {
            padding: 80px 0;
            width: 1200px;
            margin: auto;
            display: flex;
            align-items: center;
            .newsletter-text {
                width: 60%;
                display: flex;
                align-items: center;
                justify-content: center;
                .email-icon {
                    background-color: #2b2e32;
                    height: 70px;
                    width: 70px;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    border-radius: 50%;
                    margin: 0 20px 0 0;
                    i {
                        font-size: 30px;
                        color: #74797f;
                    }
                }
                h1 {
                    color: white;
                    font-size: 25px;
                }
            }
            .send-email {
                display: flex;
                align-items: center;
                justify-content: flex-end;
                width: 40%;
                input {
                    width: 70%;
                    padding: 15px 30px 15px 10px;
                    border-radius: 30px;
                    border: none;
                    margin-right: 20px;
                }
                .send {
                    background-color: #427ed1;
                    padding: 15px 30px;
                    border-radius: 30px;
                    cursor: pointer;
                    color: white;
                    font-size: 13px;
                }
            }
        }
    }
</style>