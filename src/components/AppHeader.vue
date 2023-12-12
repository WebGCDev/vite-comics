<script>
import AppNavbar from './AppNavbar.vue';
export default {
    components: { AppNavbar },
    data() {
        return {
            arrList: [
                {
                    title: 'CHARACTERS',
                    link: '#',
                },
                {
                    title: 'COMICS',
                    link: '#',
                },
                {
                    title: 'MOVIES',
                    link: '#',
                },
                {
                    title: 'TV',
                    link: '#',
                },
                {
                    title: 'GAMES',
                    link: '#',
                },
                {
                    title: 'COLLECTIBLES',
                    link: '#',
                },
                {
                    title: 'VIDEOS',
                    link: '#',
                },
                {
                    title: 'FANS',
                    link: '#',
                },
                {
                    title: 'NEWS',
                    link: '#',
                },
                {
                    title: 'SHOP',
                    link: '#',
                },
            ]

        }
    }
};
</script>

<template>
    <header>
        <div class="head-container">
            <div class="nav-container">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <app-navbar v-for="title in arrList" :key="title.title" :title="title.title" :link="title.link" />
        </div>
        <div class="jumbo"></div>
        <button><a href="">CURRENT SERIES</a></button>
    </header>
</template>

<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;

header {
    position: relative;
    background-color: white;

    .head-container {
        max-width: 1200px;
        margin: auto;
        display: flex;

        .nav-container {
            width: 100%;
            display: flex;
            align-items: center;
            height: 6rem;
            background-color: white;

            img {
                width: 28%;
            }
        }
    }

    .jumbo {
        background-image: url('../assets/img/jumbotron.jpg');
        background-size: cover;
        height: 25rem;
    }

    button {
        position: absolute;
        bottom: -1.2rem;
        left: 23rem; //Mi sembra piu bello cosi della bozza
        background-color: #0282f9;
        padding: 1rem;
        width: 12rem;
        font-weight: 1000;

        a {
            text-decoration: none;
            color: white;
        }
    }
}
</style>