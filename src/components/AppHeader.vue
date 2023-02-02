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
                    <li>characters</li>
                    <li>comics</li>
                    <li>movies</li>
                    <li>tv</li>
                    <li>games</li>
                    <li>collectibles</li>
                    <li>videos</li>
                    <li>fans</li>
                    <li>news</li>
                    <li>shop</li>
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
         background-color: aquamarine;
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
         background-color: aqua;
         border: 1px solid black;
         margin: 0 5px;
     };
    
</style>