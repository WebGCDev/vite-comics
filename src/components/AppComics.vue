<script>
export default {
    props: {
        urlImg: String,
        series: String,
        price: String,
    }
}
</script>
<template>
    <div class="cards">
        <img :src="urlImg" :alt="series" />
        <div class="text-container">
            <h3>{{ series }}</h3>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.cards {
    width: calc((100% / 6) - 2rem);
    height: 194px;
    margin: 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 1rem;

    img {
        width: 100%;
        height: 100%;
    }

    .text-container {
        h3 {
            color: white;
            font-size: .7rem;
            white-space: wrap;
            padding-top: .5rem;
        }
    }
}
</style>