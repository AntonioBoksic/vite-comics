<script>
// import { ref } from 'vue'

// defineProps({
//   msg: String,
// })

// const count = ref(0)

</script>

<!-- HTML -->
<template>

<footer>

    <!-- SEZIONE SUPERIORE FOOTER -->
        
    <section  class="footer-top">

        <div class="container">

            
            <section class="sezione-liste">

                <!-- colonna 1 -->
                <div>
                    <ul>
                    <li class="list-title">DC COMICS</li>
                    <li>Charachters</li>
                    <li>Comics</li>
                    <li>Movie</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    </ul>

                    <ul>
                        <li class="list-title">SHOP</li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>

                </div>


                <!-- colonna 2 -->
                <div>
                    <ul>
                    <li class="list-title">DC</li>
                    <li>Terms Of Use</li>
                    <li>Privacy Policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talents Workshops</li>
                    <li>CPSC</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talents Workshops</li>
                    </ul>


                </div>


                <!-- colonna 3 -->
                <div>
                    <ul>
                    <li class="list-title">SITES</li>
                    <li>Charachters</li>
                    <li>Comics</li>
                    <li>Movie</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    </ul>


                </div>

            </section>
                

            <div class="big-logo">
                
            </div>
            
            



        </div>
    </section>
        

    <!-- SEZIONE INFERIORE FOOTER -->
        
    <section class="footer-bottom">

        <div class="container">

            <div class="signup">SIGN-UP NOW!</div>
            
            <div class="followus">
                <div class="followus-title">FOLLOW US </div>
                <ul>
                    
                    
                    <li>
                        <a href="#">
                            <img src="../../public/footer-facebook.png" alt="">
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            <img src="../../public/footer-twitter.png" alt="">
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            <img src="../../public/footer-youtube.png" alt="">
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            <img src="../../public/footer-pinterest.png" alt="">
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            <img src="../../public/footer-periscope.png" alt="">
                        </a>
                    </li>
                </ul>
             </div>

        </div>


    </section>
</footer>

</template>

<!-- STILE -->

<style scoped lang="scss">


.footer-top {
    height: 300px;
    // border: white 1px solid;
    background-image: url(../../public/footer-bg.jpg);
    object-fit: contain;

    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 80%;
        height: 100%;
        margin: auto;
        // border: grey 1px solid;
        color: white;

        .sezione-liste {
            display: flex;

            ul {
                list-style: none;
                color: grey;
                margin-right: 10px;
                margin-bottom: 10px;
                font-size: 14px;

                .list-title {
                    color: white;
                    font-weight: 900;
                    margin-bottom: 10px;
                    font-size: 18px;
                }
            }
        }

        .big-logo {
            width: 300px;
            height: 100%;
            background-image: url(../../public/dc-logo-bg.png);
            background-position:center
        }
       
    }

    img {
        width: 100px;
        height: 100px;
    }

}

.footer-bottom {
    background-color: #303030;
  height: 100px;

    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 80%;
        height: 100%;
        margin: auto;
        // border: grey 1px solid;
  
        .signup {
            border: #0282f9 2px solid;
            padding: 10px 20px;
            color: white;
        }

        .followus {
            display: flex;
            justify-content: space-between;
            align-items: center;

            .followus-title {
                padding: 10px;
                color: #0282f9;
            }
        }

        ul {
        display: flex;
        list-style: none;
            
            a {
                text-decoration: none;
                color: white;
                padding: 10px;
            }
        }
    }

    
}







</style>
