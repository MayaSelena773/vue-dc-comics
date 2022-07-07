<template>
    <section class="banner">
        <div class="flex">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="dc"> 
            <p>DIGITAL COMICS</p>
        </div>

        <div class="flex">
            <img src="../assets/img/buy-comics-merchandise.png" alt="buycomics"> 
            <p>DC MERCHANDISE</p>
        </div>

        <div class="flex">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="sub"> 
            <p>SUBSCRIPTION</p>
        </div>

        <div class="flex">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="shop" class="little-img"> 
            <p>COMIC SHOP LOCATOR</p>
        </div>

        <div class="flex">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="visa"> 
            <p>PC POWER VISA</p>
        </div>

    </section>
</template>

<script>
export default {
    name:'PageBanner'
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';

.flex {
    display: flex;
    align-items: center;
    margin: 20px;
}

.banner {
    background-color: $brand_secondary_color;
    display: flex;
    justify-content: center;
    height: 200px;

    img {
        width: 50px;
        display: inline-block;
        margin-right: 5px;
    }

    .little-img {
    width: 30px;
    }

    p {
        color: white;
    }
}

</style>



