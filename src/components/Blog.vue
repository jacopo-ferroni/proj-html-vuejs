<template>
  <div class="blog-zone">
             <div class="title-blog">
                <hr size="1">
                <h1>From Our Blog</h1>
                <hr size="1">
            </div>
            <span>The latest Classic Shop news</span>
            <div class="posts">
                <div class="post">
                    <img src="@/assets/classic-shop/images/post_img_12-700x441.jpg" alt="">
                    <h3>Aenean lobortis sapien enim viverra</h3>
                    <span>September 9th, 2015 | 0 Comments</span>

                    <p>Donec finibus sit amet orci eget utricies. Praesent posoure ante ut erat fringilla.</p>
                </div>
                <div class="post">
                    <img src="@/assets/classic-shop/images/post_img_11-700x441.jpg" alt="">
                    <h3>Duis ac massa semper maximus</h3>
                    <span>September 9th, 2015 | 0 Comments</span>

                    <p>Donec finibus sit amet orci eget utricies. Praesent posoure ante ut erat fringilla.</p>
                </div>
                <div class="post">
                    <img src="@/assets/classic-shop/images/post_img_10-700x441.jpg" alt="">
                    <h3>Nunc fermit nulla eu justo sem id</h3>
                    <span>September 9th, 2015 | 0 Comments</span>

                    <p>Donec finibus sit amet orci eget utricies. Praesent posoure ante ut erat fringilla.</p>
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name : `Blog`,
}
</script>

<style scoped lang = "scss">
    .blog-zone {
        width: 1200px;
        margin: auto;
        padding: 150px 0 50px;
        display: flex;
        flex-direction: column;
        align-items: center;
        .title-blog {
            display: flex;
            align-items: center;
            width: 100%;
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
        .posts {
            margin: 50px 0;
            display: flex;
            align-items: center;
            justify-content: center;
            .post {
                padding: 0 15px;
                width: calc(100% / 3);
                img {
                    width: 100%;
                }
                h3 {
                    margin-top: 15px;
                    font-size: 18px;
                }
                p {
                    margin: 15px 0 0;
                    line-height: 30px;
                    font-size: 15px;
                }
                span {
                    font-size: 13px;
                }
            }
        }
    }
</style>