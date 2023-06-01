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
            <ul>
                <li>LINK </li>
                <li>LINK</li>
                <li>LINK </li>
                <li>LINK </li>
                <li>LINK </li>
                <li>LINK </li>
                <li>LINK </li>
                <li>LINK </li>
                <li>LINK </li>
                <li>LINK </li>

            </ul>
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
                            LINK
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            LINK
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            LINK
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            LINK
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            LINK
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
    border: white 1px solid;
    background-image: url(../../public/footer-bg.jpg);
    object-fit: contain;


}

.footer-bottom {
    background-color: #303030;
  height: 100px;

  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    margin: auto;
    border: grey 1px solid;
  
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
