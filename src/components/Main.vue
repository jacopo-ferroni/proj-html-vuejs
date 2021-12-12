<template>
  <div class="main">

        <NewArrivals />

        <Featured />

        <Collection />

        <BestSeller />

        <Information />

        <NewArrivals2 />

        <Testimonial />

        <Blog />

        <!-- DIVISORIO -->
        <hr size="1">

        <Feed />

        <BrandsLogos />

        <NewsLetter />
    </div>
</template>

<script>
import NewArrivals from "@/components/NewArrivals.vue";
import Featured from "@/components/Featured.vue";
import Collection from "@/components/Collection.vue";
import BestSeller from "@/components/BestSeller.vue";
import Information from "@/components/Information.vue";
import NewArrivals2 from "@/components/NewArrivals2.vue";
import Testimonial from "@/components/Testimonial.vue";
import Blog from "@/components/Blog.vue";
import Feed from "@/components/Feed.vue";
import BrandsLogos from "@/components/BrandsLogos.vue";
import NewsLetter from "@/components/NewsLetter.vue";

export default {
    name : `Main`,
    components : {
        NewArrivals,
        Featured,
        Collection,
        BestSeller,
        Information,
        NewArrivals2,
        Testimonial,
        Blog,
        Feed,
        BrandsLogos,
        NewsLetter,
    }
}
</script>

<style scoped lang = "scss">

    hr {
        width: 95%;
        margin: auto;
    }

</style>