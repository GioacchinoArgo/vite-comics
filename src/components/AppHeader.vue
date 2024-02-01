<script>
export default {
    name: 'AppHeader',
    data: () => ({
        links: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
        ]
    })
}
</script>

<template>
    <header>
        <figure>
            <img id="logo" src="../assets/img/dc-logo.png" alt="">
        </figure>
        <nav>
            <ul>
                <li v-for="(link, i) in links" :key="i"><a :href="link.url" :class="{ active: link.current }">{{ link.text
                }}</a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 140px;
}

ul {
    display: flex;
    flex-direction: row;
    list-style: none;
}

ul li {
    margin: 1rem;
    text-transform: uppercase;
    font-weight: 600;
    font-size: 14px;
}

ul li a.active,
ul li a:active {
    position: relative;
    color: #0282F9;
}

ul li a.active::after,
ul li a:active::after {
    content: '';
    background-color: #0282F9;
    height: 5px;
    width: 100%;
    display: block;
    position: absolute;
    left: 0;
    top: 73px;
}

nav {
    display: flex;
}
</style>