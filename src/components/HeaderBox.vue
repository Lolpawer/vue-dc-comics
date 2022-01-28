<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="@/assets/dc-logo.png" />
            </div>
            <nav>
                <ul>
                    <li v-for="nav in nav" :key="nav">{{nav.text}}</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    props: {
        nav: Array,
    }
}
</script>

<style lang="scss" scoped>

    header {
        
        .container {
            width: 1200px;
            height: 100px;
            display: flex;
            margin: 0 auto;
            justify-content: space-between;
            align-items: center;
    
            .logo {
                width: 75px;
                height: 75px;
               
                img {
                    width: 100%;
                    height: 100%;
                }
            }

            nav {
                height: 100%;

                ul{
                    height: 100%;
                    list-style: none;
                    display: flex;
                    margin: 0; //per qualche motivo si da un margin di 16px da solo?
                
                    li{
                        margin: 0 10px;
                        font-size: 12px;
                        font-weight: bold;
                        color: #464646;
                        line-height: 100px;
                        cursor: pointer;

                        &:hover{
                            color: #0282f9;
                            border-bottom: 5px solid #0282f9;
                        }
                    }
                }
            }
        }
    }

</style>