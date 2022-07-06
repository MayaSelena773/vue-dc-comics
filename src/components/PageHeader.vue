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

<style scoped>

header {
    display: flex;
    justify-content: space-between;
}

header img {
    width: 70px;
    display: inline-block;
}

.logo {
    padding: 1rem;
}

nav {
    padding: 1rem;
}

a {
    text-decoration: none;
    color: black;
    padding: 20px;
}

.flex {
    display: flex;
}

</style>

