<template>
    <header>
        <!--Header logo-->
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="logo">
        </div>

        <!--Header nav-->
        <nav>
            <ul class="flex">
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Collectibles</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">Fans</a></li>
                <li><a href="#">News</a></li>
                <li><a href="#">Shop</a></li>
            </ul>
        </nav>

    </header>
</template>

<script>
export default {
    name:'PageHeader'
}
</script>

<style lang="scss" scoped>

@import '../style/variables.scss';

header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    img {
    width: 70px;
    display: inline-block;
    }
}

.logo {
    padding: 1rem;
}

nav {
    padding: 1rem;
}

a {
    text-decoration: none;
    color: $brand_main_color;
    padding: 20px;
    text-transform: uppercase;
}

.flex {
    display: flex;
}

</style>

