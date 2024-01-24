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
    <footer>
        <div class="footer-top-container">
            <div>
               <div class="list-container">
                    <ul>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                    </ul>
                    <ul>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                    </ul>
                    <ul>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                    </ul>
                    <ul>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                    </ul>
               </div>
            </div>
            <div class="logo-container">
                <img src="../../public/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
.footer-top-container {
    background-image:url("../../public/img/footer-bg.jpg");
    display: flex;
    justify-content: space-between;
}

.list-container{
    display: flex;
    
    
}

ul {
    width: calc(100% / 3);
    flex-wrap: wrap;
    color: white;
}
</style>
