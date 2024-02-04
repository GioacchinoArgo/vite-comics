<script>
export default {
    name: 'AppMain'
}
</script>

<template>
    <main>
        <section class="upper-content">
            <div class="container">
                <h1>-- Content goes here --</h1>
            </div>
        </section>
        <section class="mid-content">
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
        <section class="lower-content">
            <div class="container">

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

.mid-content {
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
</style>