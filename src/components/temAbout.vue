<!-- 关于我 -->
<template>
    <div class="tcommonBox">
        <header>
            <h1>
                <a href="#/DetailShare" target="_blank">
                    关于我
                </a>
            </h1>
        </header>
        <section>
            <p class="">
                <img :src="this.$store.state.aboutmeObj.image?this.$store.state.aboutmeObj.image:'static/img/maoto.png'" alt="" onerror="this.onerror=null;this.src= 'static/img/maoto.png'" class="aboutmeImg">
            </p>
            <p v-html="this.$store.state.aboutmeObj.brief">{{this.$store.state.aboutmeObj.brief}}</p>
            <p>
                欢迎来到我的博客！我是一个可爱的girl，前端程序媛，喜欢各种有趣的事物，爱好各种动手的小玩意儿
            </p>
            <p>
                90后小美女😍，前端小萌新，
            </p>
            <p>
                爱美食，爱动手做美食，想长胖的尽管来。
            </p>
            <p>
                博客建于2021年5月23日.
            </p> 
        </section>
    </div>
</template>

<script>
    export default {
        data() { //选项 / 数据
            return {

            }
        },
        methods: { //事件处理器

        },
        components: { //定义组件

        },
        created() { //生命周期函数

        }
    }
</script>

<style>
.aboutmeImg{
    max-width:100%;
    /*height:300px;*/
}
.tcommonBox p a{
    color:#01AAED!important;
}
.tcommonBox p a:hover{
    color:#48456d!important;
}
.tcommonBox p i{
    font-style: italic;
}
.tcommonBox p b{
    font-weight: bold;
}
</style>
