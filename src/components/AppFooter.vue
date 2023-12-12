<script>
export default {
    data() {
        return {
        }
    }
};
</script>

<template>
    <footer>
        <section class="footer-up">
            <div class="options">
                <div class="option">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <p>DIGITAL COMICS</p>
                </div>
                <div class="option">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <p>DC MERCHANDISE</p>
                </div>
                <div class="option">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <p>SUBSCRIPTION</p>
                </div>
                <div class="option">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <p>COMIC SHOP LOCATOR</p>
                </div>
                <div class="option">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <p>DC POWER VISA</p>
                </div>

            </div>
        </section>
        <section class="footer-mid">
            <div class="contacts">
                <div class="links">
                    <div class="column">
                        <ul>
                            <li class="title">DC COMICS</li>
                            <li><a href="">Character</a></li>
                            <li><a href="">Comics</a></li>
                            <li><a href="">Movies</a></li>
                            <li><a href="">Tv</a></li>
                            <li><a href="">Games</a></li>
                            <li><a href="">Videos</a></li>
                            <li><a href="">News</a></li>
                        </ul>
                        <ul>
                            <li class="title">SHOP</li>
                            <li><a href="">Shop DC</a></li>
                            <li><a href="">Shop DC Collectibles</a></li>
                        </ul>

                    </div>
                    <ul>
                        <li class="title">DC</li>
                        <li><a href="">Terms Of Use</a></li>
                        <li><a href="">Privacy policy (New)</a></li>
                        <li><a href="">Ad Choices</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">Talent Workshops</a></li>
                        <li><a href="">CPSC Certeficates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                    <ul>
                        <li class="title">SITES</li>
                        <li><a href="">DC</a></li>
                        <li><a href="">MAD Magazine</a></li>
                        <li><a href="">DC Kids</a></li>
                        <li><a href="">DC Universe</a></li>
                        <li><a href="">DC Power Visa</a></li>
                    </ul>

                </div>
                <div class="image">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </section>
        <section class="footer-bot">
            <div class="socials">
                <button>SIGN-UP NOW!</button>
                <div class="social">
                    <h3>FOLLOW US</h3>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </section>
    </footer>
</template>

<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;

.footer-up {
    background-color: #0282f9;

    .options {
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 8rem;
        max-width: 1200px;
        margin: auto;

        .option {
            display: flex;
            align-items: center;
            padding-inline: 1.5rem;
        }

        img {
            width: 2.2rem;
        }

        p {
            color: white;
            padding-inline: .7rem;
            white-space: nowrap;
            font-size: .9rem;
        }
    }
}

.footer-mid {
    background-image: url('../assets/img/footer-bg.jpg');
    overflow: hidden;

    .contacts {
        height: 20rem;
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 1200px;
        margin: auto;
    }

    .links {
        display: flex;
        gap: 1.5rem;

        .column {
            display: flex;
            flex-direction: column;
        }

        .title {
            font-weight: 700;
            color: white;
            margin-bottom: .5rem;
            margin-top: .5rem;
        }

        li {
            list-style: none;

            a {
                text-decoration: none;
                color: gray;
                font-size: .7rem;
            }
        }
    }
}

.footer-bot {
    background-color: rgb(48, 48, 48);

    .socials {
        display: flex;
        align-items: center;
        justify-content: space-between;
        max-width: 1200px;
        margin: auto;
        height: 5rem;

        button {
            background-color: transparent;
            color: white;
            border: 2px solid #0282f9;
            padding: .7rem;
        }

        .social {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        h3 {
            color: #0282f9;
            font-size: 1.1rem;
        }
    }
}
</style>