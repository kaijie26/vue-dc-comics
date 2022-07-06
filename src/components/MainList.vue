<!-- HTML -->
<template>
    <section>
        <!-- Main-list -->
        <ul class="main-list">
            <li v-for="(icon, index) in iconsList" :key="index">
                <img :src="icon.imgPath" :alt="icon.imgAlt">
                <a :href="icon.url">{{ icon.text }}</a>
            </li>
            

        </ul>
        
    </section>
    
</template>


<!-- JAVASCRIPT -->
<script>
export default {
    name: 'MainList',
    data(){
        return{
            iconsList: [
                {
                    text: 'DIGITAL COMICS',
                    url: '#',
                    imgPath: require('../assets/img/buy-comics-digital-comics.png'),
                    imgAlt: 'buy-digital',
                    
                },
                {
                    text: 'DC MERCHANDISE',
                    url: '#',
                    imgPath: require('../assets/img/buy-comics-merchandise.png'),
                    imgAlt: 'buy-merchandise',
                    
                },
                {
                    text: 'SUBSCRIPTION',
                    url: '#',
                    imgPath: require('../assets/img/buy-comics-subscriptions.png'),
                    imgAlt: 'buy-digital',
                    
                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    url: '#',
                    imgPath: require('../assets/img/buy-comics-shop-locator.png'),
                    imgAlt: 'shop-locator',
                    
                },
                {
                    text: 'DC POWER VISA',
                    url: '#',
                    imgPath: require('../assets/img/buy-dc-power-visa.svg'),
                    imgAlt: 'power-visa',
                    
                },
            ]
        }
    }
    
}
</script>


<!-- CSS -->
<style lang="scss" scoped>
@import '../style/variables';
section{
    background-color: $page_primary_color;
    height: 120px;
    // Main-List
    .main-list{
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100%;
        
        li{
            padding: 30px;

            img{
                width: 35px;
                vertical-align: middle;
            }
            
            a{
                margin-left: 10px;
                text-decoration: none;
                color: $page_secondary_color;
                font-size: 13px;
                vertical-align: middle;
            }
        }
    }

}

</style>