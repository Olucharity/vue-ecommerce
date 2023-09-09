<template>
    <div class="sale">
        whats good

        <div class="product">
            <img src="../assets/image1.jpg" alt="">
            <img src="../assets/image2.jpg" alt="">
            <img src="../assets/image3.jpg" alt="">
            <img src="../assets/image4.jpg" alt="">
            <img src="../assets/image5.jpg" alt="">
            <img src="../assets/image6.jpg" alt="">
        </div>
    </div>
</template>

<script>
export default{}
</script>

<style>
    .sale{
        margin: 80px 0;
        width: 100%;
        display: grid;
        place-items: center;
    }
    .product{
        display: grid;
        grid-template-columns: auto auto auto;
        place-items: center;
        gap: 50px 30px;
        width: 1100px;
    }
    .product img{
        width: 340px;
        box-shadow: 0 0 4px 0 #d1d0d0;
    }
</style>