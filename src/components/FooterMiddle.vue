<template>
    <div class="background">
        <div class="container">
            <div class="text">
                <div class="column">
                    <ul>
                        <li class="title"> DC COMICS</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                        <li class="title">SHOP</li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <div class="column">
                    <ul>
                        <li class="title">DC</li>
                        <li>Terms of Use</li>
                        <li>Privacy Policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Rating</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div class="column">
                    <ul>
                        <li class="title">SITES</li>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>
            <div class="big-logo">
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style lang="scss" scoped>

    .background {
        background-image: url("../assets/footer-bg.jpg");
        background-size: cover;

        .container {
            background-image: none;
            height: 300px;
            width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;

            .text {
                height: 100%;
                display: flex;
                font-family: Arial, Helvetica, sans-serif;

                .column {
                    
                    ul {
                        list-style: none;

                        li {
                            color:#959595;
                            font-size: 12px;
                            padding: 2px 0;
                        }

                        .title {
                            color: #fff;
                            padding: 13px 0;
                            font-weight: bold;
                            font-size: 20px;
                        }
                    }
                }
            }

            .big-logo {
                background-image: url("../assets/dc-logo-bg.png");
                background-size: cover;
                background-position: center;
                width: 45%;
            }
        }
    }

</style>