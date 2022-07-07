<!-- HTML -->
<template>
    <footer>
            <!-- Footer-Top -->
            <div class="footer-top">
                <div class="container">
                    <div class="footer-container">
                        <div class="menu-col">
                            <ul class="footer-menu">
                                <li>
                                    <h3>DC COMICS</h3>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                
                                
                                <ul class="footer-menu">
                                    <li>
                                        <h3>SHOP</h3>
                                    </li>
                                    <li>
                                        <a href="#">item</a>
                                    </li>
                                    <li>
                                        <a href="#">item</a>
                                    </li>

                                    
                                </ul>
                    

                            </ul>

                            <ul class="footer-menu">
                                <li>
                                    <h3>DC</h3>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                            </ul>

                            <ul class="footer-menu"> 
                                <li>
                                    <h3>SITES</h3>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                <li>
                                    <a href="#">item</a>
                                </li>
                                
                            </ul>

                        </div>
                        

                        <div class="footer-logo">
                            <img src="../assets/img/dc-logo-bg.png" alt="dc-logo-bc">
                        </div>

                    </div>

                    
                    
                    
                </div>
                

            </div>

            <!-- Footer-Bottom -->
            <div class="footer-bottom">
                <div class="container">
                    <div class="footer-container">
                        <!-- BTN -->
                        <button class="btn">
                            <a href="#">SIGN-UP NOW!</a>
                        </button>

                        <!-- Social -->
                        <div class="social">
                            <h3>
                                FOLLOW US
                            </h3>
                            
                            <!-- Social-icons -->
                            <ul class="social-list" >
                                <li>
                                    <a href="#">
                                        <img src="../assets/img/footer-facebook.png" alt="facebook-img">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img src="../assets/img/footer-facebook.png" alt="facebook-img">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img src="../assets/img/footer-facebook.png" alt="facebook-img">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img src="../assets/img/footer-facebook.png" alt="facebook-img">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img src="../assets/img/footer-facebook.png" alt="facebook-img">
                                    </a>
                                </li>
                            </ul>

                            

                        </div>

                    </div>

                </div>
                

            </div>
        
    </footer>
    
</template>

<!-- JAVASCRIPT -->
<script>
export default {
    
}
</script>

<!-- CSS -->
<style lang="scss" scoped>
@import '../style/variables';

.footer-container{
    display: flex;
    justify-content: space-between;
}

.footer-top{
    background-image: url('../assets/img/footer-bg.jpg');
    height: 300px;

        .menu-col{
            display: flex;

            .footer-menu{
                margin-right: 30px;
 
                li{

                    h3{
                    color: $page_secondary_color;
                    padding-top: 15px;

                    }

                    a{
                        text-decoration: none;
                        color: lightgray;
                        font-size: 12px;
                        
                    }

                }

            }
        }


        .footer-logo{
            width: 400px;
            position: relative;
            bottom: 50px
        }

}

.footer-bottom{
    background-color: #303030;
    height: 100px;
    position: absolute;
    width: 100%;
    z-index: 99;
    display: flex;
    align-items: center;

    .footer-container{
        .btn{
            background-color: #303030;
            border: 2px solid $page_primary_color ;
            padding: 5px 10px;

            a{
                text-decoration: none;
                color: white;
                
            }
        }

        .social{
            display: flex;
            align-items: center;

            h3{
                color:$page_primary_color;
            }

            .social-list{
            
                display: flex;

                a{
                    padding: 5px;

                    img{
                    width: 30px;
                    
                    }

                }

                

            

            }

            
        }


    }

    

   

}

</style>