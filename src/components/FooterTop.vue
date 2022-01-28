<template>
    <div>
        <div class="container">
            <div>
                <img src="@/assets/buy-comics-digital-comics.png"/>
                DIGITAL COMICS
            </div>
            <div>
                <img src="@/assets/buy-comics-merchandise.png"/>
                DC MERCHANDISE
            </div>
            <div>
                <img src="@/assets/buy-comics-subscriptions.png"/>
                SUBSCRIPTION
            </div>
            <div>
                <img src="@/assets/buy-comics-shop-locator.png"/>
                COMIC SHOP LOCATOR
            </div>
            <div>
                <img src="@/assets/buy-dc-power-visa.svg" class="power-visa"/>
                DC POWER VISA
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style lang="scss" scoped>

    div {
        background-color: #0282f9;

        .container {
            width: 1200px;
            margin: 0 auto;
            height: 175px;
            display: flex;
            justify-content: space-between;
            align-items: center;

            div {
                color: #fff;
                font-size: 13px;
                display: flex;
                align-items: center;

                img {
                    height: 60px;
                    margin: 0 15px;
                }

                .power-visa {
                    height: 35px;
                }
            }
        }
    }

</style>