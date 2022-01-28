<template>
    <div>
        <main-jumbotron/>
        <div class="background">
            <div class="container">
                <div class="current-series">CURRENT SERIES</div>
                <div class="series-row">
                    <div class="comic-box" v-for="comic in comics" :key="comic">
                        <div class="img-box">
                            <img :src="comic.thumb" />
                        </div>
                        <p>{{comic.series.toUpperCase()}}</p>
                    </div>
                </div>
                <div class="load-more">LOAD MORE</div>
            </div>
        </div>
    </div>
</template>

<script>
import MainJumbotron from './MainJumbotron.vue'

export default {
    components: {
        MainJumbotron,
    },
    props: {
        comics: Array
    }
}

</script>

<style lang="scss" scoped>
    .background {
        background-color: #1c1c1c;

        .container {
            width: 1200px;
            margin: 0 auto;
            padding: 30px 0;
            position:relative;

            .current-series {
                position: absolute;
                font-size: 25px;
                color: #fff;
                font-weight: bold;
                background-color: #0282f9;
                padding: 10px 30px;
                top: -25px;
                left: -15px;

            }
            
            .series-row {
                display: flex;
                flex-wrap: wrap;
                justify-content: space-between;
                padding: 20px 0;

                .comic-box {
                    width: 175px;
                    padding-bottom: 20px;
                    
                    .img-box{
                        height: 175px;
                    
                        img {
                            width: 175px;
                            height: 175px;
                            object-fit: cover;
                            object-position: top;

                        }
                    }

                    p {
                        color: #fff;
                        font-size: 14px;
                    }
                }
            }

            .load-more {
                width: fit-content;
                margin: 0 auto;
                color: #fff;
                font-weight: bold;
                background-color: #0282f9;
                padding: 10px 60px;
                font-size: 12px;
                cursor: pointer;
            }
        }
    }

</style>