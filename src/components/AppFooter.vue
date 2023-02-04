<script>
export default{
    name: 'AppFooter'
}
</script>

<template>
    <footer>
        <div class="up-footer">
            <div class="container-center-up">
                <ul>
                    <li>
                        <div class="img-footer">
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        </div>
                        <div class="testo">
                            DIGITAL COMICS
                        </div>
                    </li>
                    <li>
                        <div class="img-footer">
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        </div>
                        <div class="testo">
                            DC MERCHANDISE
                        </div>
                    </li>
                    <li>
                        <div class="img-footer">
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        </div>
                        <div class="testo">
                            SUBSCRIPTION
                        </div>
                    </li>
                    <li>
                        <div class="img-footer">
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        </div>
                        <div class="testo">
                            COMIC SHOP LOCATOR
                        </div>
                    </li>
                    <li>
                        <div class="img-footer">
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        </div>
                        <div class="testo">
                            DC POWER VISA
                        </div>
                    </li>
                    
                </ul>
            
            </div>
        </div>
        <div class="middle-footer">
            <div class="container-center-middle">
                <div>
                    <div>
                        DC COMICS
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>
                    <div>
                        SHOP
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                </div>
                <div>
                    DC
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy Policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div>
                    SITES
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="down-footer">
            <div class="container-center-down">
                <div id="sign-up">
                    SIGN-UP NOW!
                </div>
                <div id="down-list">
                    <ul>
                        <li id="follow-us">FOLLOW US</li>
                        <li>
                            <font-awesome-icon icon="fa-brands fa-square-facebook" />
                        </li>
                        <li>
                            <font-awesome-icon icon="fa-brands fa-square-twitter" />
                        </li>
                        <li>
                            <font-awesome-icon icon="fa-brands fa-square-youtube" />
                        </li>
                        <li>
                            <font-awesome-icon icon="fa-brands fa-square-pinterest" />                        
                        </li>
                        <li>
                            <font-awesome-icon icon="fa-solid fa-location-dot" />
                        </li>
                    </ul>
                </div>
            </div>
        </div>
            
        
        
    </footer>
</template>

<style lang=scss scoped>
    footer{
         height: 400px;
         width: 100%;
    };
    .up-footer{
        height: 100px;
        background-color: #0282f9;
        display: flex;
        justify-content: center;
        };

    .container-center-up{
    height: 100%;
    width: 80%;
    display: flex;
    align-items: center;
    justify-content: center;
    };

    .up-footer .container-center-up > ul{
        width: 100%;
        list-style: none;
        display: flex;
        justify-content: space-around
        
    };
    .up-footer .container-center-up > ul > li{
        height: 50px;
        min-width: 100px;
        display: flex;
    };

    .up-footer .container-center-up > ul > li > div > img{
        height: 100%;
        width: 100%;
    };

    .up-footer .container-center-up > ul > li .testo{
        margin-left: 10px;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;

    };


    .middle-footer{
        height: 60vh;
        background-color: gray;
        display: flex;
        justify-content: center;
        color: white;
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        
    };

    .container-center-middle{
        height: 100%;
        width: 80%;
        display: flex;
        padding: 20px;
    };

    .container-center-middle > div{
        margin-right: 20px;
    };

    .container-center-middle li{
        color: #7a8071;
        margin: 5px 0;
        list-style: none;
    };



    .down-footer{
        height: 100px;
        background-color: #303030;
        display: flex;
        justify-content: center;
    };
    .container-center-down{
    height: 100%;
    width: 80%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    };

    .container-center-down #sign-up{
        border: 2px solid #0282f9;
        height: 50px;
        min-width: 100px;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 0 10px;

    };


    .container-center-down #down-list ul {
        display: flex;

    };

    .container-center-down #down-list ul > li {
        list-style: none;
        margin: 0 10px;
        height: 50px;
        min-width: 50px;
        display: flex;
        justify-content: center;
        align-items: center;

    };

    .container-center-down #down-list ul > li > * {
        font-size: 30px;
        color: white
        
    };

    .container-center-down #down-list #follow-us {
        color: #0282f9;
        font-weight: bold;

    }

</style>