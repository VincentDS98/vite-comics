<script>
import ProductVue from './Product.vue';

export default {
    data() {
        return {

        };
    },
    components: {
        Product
    }, 
    methods: {

    }
}
</script>

<template>
    <Product/>
    <main>
        <div class="main-top">
            <div class="comics-container">
                <Product
                    v-for="(fumetto,i) in fumetteria"
                    :key="i"
                    :series = "fumetteria.series"
                    :thumb = "fumetteria.thumb"
                />
            </div>
        </div>
        <div class="main-container">
            <ul>
                <li>DIGITAL COMICS</li>
                <li>LINK</li>
                <li>LINK</li>
                <li>LINK</li>
                <li>LINK</li>
            </ul>

        </div>
    </main>
</template>

<style lang="scss" scoped>
.main-top{
    background-color: black;
    width: 700px;

   

}

.comics-container{
    
    display: flex;
}
.main-container {
    background-color: blue;
    color:white;
    padding: 50px;
}

ul{
        display:flex; 
        list-style: none;
        justify-content:center;
        text-decoration: none;
        font-weight: bold;
            
    }

li{
                margin-right: 100px;
            
            }
</style>
