<script>
export default {
    data() {
        return {

        };
    },
   props: {
    thumb:String
    series: String
    }
}
</script>

<template>
    <div class="single-product">
        <div>
            <img :src="thumb" :alt="series">
        </div>

        <h2>
            {{ series }}
        </h2>
    </div>

</template>



<style lang="scss" scoped>
.single-product {
    padding: 25px;
}

img {
    width: 100%;
}



</style>