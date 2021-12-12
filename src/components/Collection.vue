<template>
  <div class="collection-zone">
            <div class="collection-first">
                <h1>Winter Collection</h1>
                <h3>STYLISH AND WARM</h3>
                <div class="button-view-more">
                    VIEW MORE
                </div>
            </div>
            <div class="collection-second">
                <h1>Spring Collection</h1>
                <h3>BRIGHT AND COLORFUL</h3>
                <div class="button-view-more">
                    VIEW MORE
                </div>
            </div>
            <div class="collection-third">
                <h1>Autumn Collection</h1>
                <h3>RICH AND COMFORTABLE</h3>
                <div class="button-view-more">
                    VIEW MORE
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name : `Collection`,
}
</script>

<style scoped lang = "scss">
    .collection-zone {
        background-color: green;
        height: 615px;
        display: flex;
        .collection-first {
            width: calc(100% / 3);
            height: 100%;
            background-image: url("../assets/classic-shop/images/winter_collection_bg.jpg");
            background-size: cover;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-end;
            padding-bottom: 100px;
            color: white;
        }
        .collection-second {
            width: calc(100% / 3);
            height: 100%;
            background-image: url("../assets/classic-shop/images/spring_collection_bg.jpg");
            background-size: cover;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-end;
            padding-bottom: 100px;
            color: white;
        }
        .collection-third {
            width: calc(100% / 3);
            height: 100%;
            background-image: url("../assets/classic-shop/images/autumn_collection_bg.jpg");
            background-size: cover;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-end;
            padding-bottom: 100px;
            color: white;
        }
        h1 {
            font-size: 50px;
        }
        h3 {
            font-size: 25px;
            padding: 10px 0;
        }
        .button-view-more {
            cursor: pointer;
            background-color: rgba($color: #ffffff, $alpha: 0.1);
            padding: 10px 25px;
            border: 3px solid white;
            border-radius: 50px;
            font-size: 13px;
        }
    }
</style>