<!-- HTML -->
<template>
    <header>
        <div class="container">
            <div class="header-container">
                <!-- Logo -->
                <div class="logo">
                    <img src="../assets/img/dc-logo.png" alt="dc-logo">
                </div>

                <!-- List-Menu -->
                <nav>
                    <ul class="menu-list">
                        <li v-for="(link, index) in menuLinks" :key="index" :class="{ 'current': link.current === true }">
                            <a href="#">{{ link.text }}</a>
                        </li>
                    </ul>
                    
                </nav>

            </div>

        </div> 
        
    </header>

</template>

<!-- JAVASCRIPT -->
<script>
export default {
    name: "PageHeader",
    data(){
        return {
            menuLinks: [
                {
                    text: 'CHARACTERS',
                    current: false,
                    url: '#',
                },
                {
                    text: 'COMICS',
                    current: true,
                    url: '#',
                },
                {
                    text: 'MOVIES',
                    current: false,
                    url: '#',
                },
                {
                    text: 'TV',
                    current: false,
                    url: '#',
                },
                {
                    text: 'GAMES',
                    current: false,
                    url: '#',
                },
                {
                    text: 'COLLECTIBLES',
                    current: false,
                    url: '#',
                },
                {
                    text: 'VIDEOS',
                    current: false,
                    url: '#',
                },
                {
                    text: 'FANS',
                    current: false,
                    url: '#',
                },
                {
                    text: 'NEWS',
                    current: false,
                    url: '#',
                },
                {
                    text: 'SHOP',
                    current: false,
                    url: '#',
                },
                
                
            ]
        }
    }
    
}
</script>


<!-- CSS -->
<style lang="scss" scoped>
@import '../style/variables';

// Header-Container
.header-container{
    background-color: $page_secondary_color ;
    height: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;

    // Logo
    .logo{
        width: 70px;

    }

    // Nav
    .menu-list{
        display: flex;

        li{
            margin: 13px;
            line-height: 100px;

            a{
            color: black;
            text-decoration: none;
            font-size: 13px;

            }

            &.current{
                border-bottom: 5px solid $page_primary_color;
                
                a{
                    color: $page_primary_color;
                    line-height: 100px;
                    
                }
                
            }
        }

        
    }

}

</style>