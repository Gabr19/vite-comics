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

                        </div>
                        <div class="testo">

                        </div>
                    </li>
                    <li>
                        <div class="img-footer">

                        </div>
                        <div class="testo">

                        </div>
                    </li>
                    <li>
                        <div class="img-footer">

                        </div>
                        <div class="testo">

                        </div>
                    </li>
                    <li>
                        <div class="img-footer">

                        </div>
                        <div class="testo">

                        </div>
                    </li>
                    <li>
                        <div class="img-footer">

                        </div>
                        <div class="testo">

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
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                        </ul>
                    </div>
                    <div>
                        SHOP
                        <ul>
                            <li></li>
                            <li></li>
                        </ul>
                    </div>
                </div>
                <div>
                    DC
                    <ul>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                </div>
                <div>
                    SITES
                    <ul>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="down-footer">
            <div class="container-center-down">
                <div id="sign-up">

                </div>
                <div id="down-list">
                    <ul>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
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
        background-color: #303030;
        height: 50px;
        min-width: 100px;
    };
    .middle-footer{
        height: 250px;
        background-color: gray;
        display: flex;
        justify-content: center;
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
        background-color: #0282f9;
        height: 50px;
        width: 100px;
    };


    .container-center-down #down-list ul {
        display: flex;

    };

    .container-center-down #down-list ul > li {
        list-style: none;
        margin: 0 10px;
        height: 50px;
        width: 50px;
        border: 1px solid black;
        background-color: #0282f9
    };




    




</style>