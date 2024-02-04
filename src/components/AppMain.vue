<script>
import ComicsCard from './ComicsCard.vue';
export default {
    name: 'AppMain',
    props: {
        comics: Array
    },
    components: { ComicsCard }
}
</script>

<template>
    <main>
        <section id="comics-list" class="upper-content">
            <div class="container card-container">
                <ComicsCard v-for="comic in comics" :key="comic.series" :image="comic.thumb" :title="comic.series" />
            </div>
        </section>
        <section class="lower-content">
            <div class="container">
                <ul>
                    <li><img src="../assets/img/buy-comics-digital-comics.png">digital comics</li>
                    <li><img src="../assets/img/buy-comics-merchandise.png">dc merchandise</li>
                    <li><img src="../assets/img/buy-comics-subscriptions.png">subscription</li>
                    <li><img src="../assets/img/buy-comics-shop-locator.png">comic shop locator</li>
                    <li><img src="../assets/img/buy-dc-power-visa.svg">dc power visa</li>
                </ul>
            </div>
        </section>
    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: blue;
    color: #fff;
}

.upper-content {
    background-color: #1C1C1C;
    padding: 4rem 0;

    h1 {
        font-size: 30px;
    }
}

.lower-content {
    background-color: #0282F9;
    display: flex;
    justify-content: space-around;
    align-items: center;

    ul {
        display: flex;
        flex-direction: row;
        list-style: none;

        li:last-child img {
            height: 40px;
        }

        li {
            text-transform: uppercase;
            font-weight: 300;
            font-size: 16px;
            color: #fff;
            display: flex;
            align-items: center;
            padding: 3rem;
            cursor: pointer;

            img {
                height: 60px;
                margin-right: 10px;
            }
        }
    }
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 2rem;

    .comics-card {
        flex-basis: 15%;

    }
}
</style>