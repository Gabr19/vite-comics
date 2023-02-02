<script>
export default{
    name: 'AppFooter'
}
</script>

<template>
    <footer>
        <div class="up-footer">up-footer</div>
        <div class="middle-footer">middle-footer</div>
        <div class="down-footer">down-footer</div>
    </footer>
</template>

<style lang=scss scoped>
    footer{
        // display: flex;
        // justify-content: space-around;
         height: 400px;
         width: 100%;
    .up-footer{
            height: 100px;
            background-color: #0282f9;
        }
    .middle-footer{
        height: 250px;
        background-color: gray;
    }
    .down-footer{
        height: 100px;
        background-color: #303030;
    }
    };
    




</style>