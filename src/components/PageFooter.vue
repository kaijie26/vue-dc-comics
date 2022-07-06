<!-- HTML -->
<template>
    <footer>
            <!-- Footer-Top -->
            <div class="footer-top">
                <div class="container">
                    <div class="footer-container">
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

                        <div class="footer-logo">
                            <img src="../assets/img/dc-logo-bg.png" alt="dc-logo-bc">
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

.footer-top{
    background-image: url('../assets/img/footer-bg.jpg');
    height: 300px;

    .footer-container{
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

        .footer-logo{
            width: 500px;
        }


    }



    

}

</style>