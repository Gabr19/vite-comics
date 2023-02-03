<script>
export default{

 name: 'AppHeader'
}

</script>

<template>
    <header>
        <div class="container-center">
            <div id="logo">
                <img src="../assets/img/favicon.ico" alt="">
        
            </div>
            <div id="lista">
                <ul>
                    <li>CHARACTERS</li>
                    <li id="active">COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </div>
        </div>
        

    </header>
</template>

<style lang=scss scoped>

    header{
        display: flex;
        justify-content: center
         
    };

    .container-center{
        height: 100%;
        width: 80%;
        display: flex;
        justify-content: space-between;
    };
    
    
     #logo{
         height: 50px;
         width: 50px;
         display: flex;
         padding: 5px;
     };

     #lista{
        display: flex;
        align-items: center;
     }
     ul{
         display: flex;
         height: 100%;
     };
     ul > li{
         list-style: none;
         height: 100%;
         margin: 0 5px;
         display: flex;
         align-items: center;
         font-weight: bold;

     };

     #active{
        border-bottom: 3px solid #0282f9;
        color: #0282f9;
     }
    
</style>