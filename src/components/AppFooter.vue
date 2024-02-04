<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <footer>
        <section class="upper-footer">
            <div class="container">
                <div class="footer-row">
                    <div class="footer-col">
                        <h2>dc comics</h2>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                        <h2>shop</h2>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h2>dc</h2>
                        <ul>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">subscription</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h2>Sites</h2>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <section class="lower-footer">
            <div class="container">
                <div class="footer-row">
                    <div class="footer-col">
                        <button>sign-up now</button>
                    </div>
                    <div class="socials">
                        <ul>
                            <li><span>follow us</span></li>
                            <li><a href="#"><i class="fa-brands fa-facebook-f"></i></a></li>
                            <li><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
                            <li><a href="#"><i class="fa-brands fa-youtube"></i></a></li>
                            <li><a href="#"><i class="fa-brands fa-pinterest-p"></i></a></li>
                            <li><a href="#"><i class="fa-brands fa-periscope"></i></a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
    </footer>
</template>

<style lang="scss" scoped>
.upper-footer {
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    padding: 3rem 0;

    .footer-row {
        display: flex;
        gap: 50px;

        h2 {
            margin-bottom: 1rem;
            color: #fff;
            text-transform: uppercase;
        }

        .footer-col ul {
            list-style: none;
            line-height: 20px;

            a {
                list-style: none;
                color: gray;
                margin-bottom: 0.5rem;
                font-size: 0.75rem;
            }
        }
    }
}


.lower-footer {
    background-color: #303030;
    padding: 2rem 0;

    .footer-row {
        display: flex;
        align-items: center;
        justify-content: space-between;

        button {
            text-transform: uppercase;
            font-size: 1rem;
            padding: 0.8rem 1rem;
            font-weight: 600;
            border: 2px solid #0282F9;
            background-color: #303030;
            color: #fff;
            cursor: pointer;
        }
    }
}

.socials {

    span {
        text-transform: uppercase;
        font-size: 1.5rem;
        margin: 0 5px;
        font-weight: 800;
        color: #0282F9;
    }
}

.socials {
    ul {
        list-style: none;
        display: flex;
        flex-direction: row;
        align-items: center;
        gap: 10px;

        i {
            background-color: #797979;
            width: 35px;
            height: 35px;
            font-size: 25px;
            border-radius: 50%;
            color: #303030;
            text-align: center;
            line-height: 35px;
        }
    }
}
</style>