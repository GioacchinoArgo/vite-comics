<script>
export default {
    name: 'ComicsCard',
    props: {
        image: String,
        title: String
    }
}
</script>

<template>
    <div class="comics-card">
        <img :src="image" :alt="title">
        <h2>{{ title }}</h2>
    </div>
</template>

<style lang="scss" scoped>
.comics-card {
    padding: 20px;
}
</style>