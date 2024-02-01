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
                    <li><img src="../assets/img/buy-comics-digital-comics.png" alt="">digital comics</li>
                    <li><img src="../assets/img/buy-comics-merchandise.png" alt="">dc merchandise</li>
                    <li><img src="../assets/img/buy-comics-subscriptions.png" alt="">subscription</li>
                    <li><img src="../assets/img/buy-comics-shop-locator.png" alt="">comic shop locator</li>
                    <li><img src="../assets/img/buy-dc-power-visa.svg" alt="">dc power visa</li>
                </ul>
            </div>
        </section>
        <section class="lower-content">

        </section>
    </main>
</template>

<style scoped>
main {
    background-color: blue;
    color: #fff;
}

.upper-content {
    background-color: #1C1C1C;
    padding: 1.5rem 0;
}

.upper-content h1 {
    font-size: 30px;
}

.mid-content {
    background-color: #0282F9;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 3rem 0;
}

.mid-content ul {
    display: flex;
    flex-direction: row;
    list-style: none;
}

.mid-content ul li {
    text-transform: uppercase;
    font-weight: 300;
    font-size: 16px;
    color: #fff;
    display: flex;
    align-items: center;
    margin: 1rem;
}

.mid-content ul li img {
    margin: 0 .50rem 0 0;
    height: 50%;
}
</style>