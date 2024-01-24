<script>
export default {
    data() {
        return {

        };
    },
    methods: {

    }
}
</script>

<template>
    <header>
        <div class="header-top">
            <div>
                <img id="logo" src="../../public/img/dc-logo.png" alt="">
            </div>
            <ul>
                <li>Characters</li>
                <li>Movies</li>
                <li>Comics</li>
                <li>Tv</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Video</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>

            </ul>

        </div>

        
    </header>
</template>

<style lang="scss" scoped>
.header-top{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px;


    
}



#logo {
        margin-left: 300px;
        width:20%;
    }

 ul{
        display:flex; 
        list-style: none;
        justify-content: space-between;
        text-decoration: none;
        font-weight: bold;
            
 }

li{
    margin-right: 50px;
            
}
html{
    font-family: Arial, Helvetica, sans-serif;
}


img {
    width: 100%;
}






</style>
