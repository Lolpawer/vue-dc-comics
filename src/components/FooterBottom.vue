<template>
    <div>
        <div class="container">
            <div class="button">
                SIGN-UP NOW!
            </div>
            <div class="logos">
                <span>FOLLOW US</span>
                <img src="@/assets/footer-facebook.png" />
                <img src="@/assets/footer-twitter.png" />
                <img src="@/assets/footer-youtube.png" />
                <img src="@/assets/footer-pinterest.png" />
                <img src="@/assets/footer-periscope.png" />
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style lang="scss" scoped>

    div {
        background-color: #303030;

        .container {
            width: 1200px;
            margin: 0 auto;
            height: 100px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-family: Arial, Helvetica, sans-serif;
            font-weight: bold;

            .button {
                border: 2px solid #0282f9;
                padding: 15px 12px;
                color: #fff;
            }

            .logos {

                span{
                    color: #0282f9;
                    margin: 0 10px;
                    font-size: 20px;
                    vertical-align: middle;
                }

                img {
                    vertical-align: middle;
                    margin: 0 10px;
                }
            }
        }
    }

</style>