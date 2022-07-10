<template>
    <footer>

        <!--Footer Top-->
        <section class="footer_top">
            <div class="lists_container">
                <!--Left Nav-->
                    <div class="nav-list">
                        <h3>dc comics</h3>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>Tv</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>

                        <h3>shop</h3>
                        <ul>
                            <li>Shop dc</li>
                            <li>Shop dc Collectibles</li>
                        </ul>
                    </div>

                    <!--Central Nav-->
                    <div class="nav-list">
                        <h3>dc</h3>
                        <ul>
                            <li>Terms Of Use</li>
                            <li>Privacy Policy (New)</li>
                            <li>Add Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscription</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>

                    <!--Right Nav-->
                    <div class="nav-list">
                        <h3>sites</h3>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
            </div>

            <div class="padd-img">
                <img src="../assets/img/dc-logo-bg.png" alt="logobig" class="big-logo">
            </div>
        </section>

        <!--Footer Bottom-->
        <section>

        </section>

    </footer>
</template>

<script>
export default {
    name:'PageFooter'
}
</script>

<style lang="scss" scoped>

footer {

    .footer_top {
        background-image: url('../assets/img/footer-bg.jpg');
        background-size: cover;
        display: flex;
        height: 400px;
        overflow: hidden;

        .big-logo {
        width: 450px;
        }

        .lists_container {
        margin-left: 4.5rem;
        display: flex;
        flex-direction: row;

            .nav-list {
            margin: 1rem;
            color: white;

                h3 {
                margin: 1rem 0;
                text-transform: uppercase;
                }
            }
        } 
    }
}

</style>


