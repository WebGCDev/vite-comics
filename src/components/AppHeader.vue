<script>
</script>

<template>
    <header>
        <nav>
            <img src="../assets/img/dc-logo.png" alt="">
            <ul class="head_list">
                <li>CHARACTER</li>
                <li class="bluemode">COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;

header {
    background-color: white;
}

.bluemode {
    &:hover {
        color: #0282f9;
        cursor: pointer;
    }
}

nav {
    max-width: 1000px;
    margin: auto;
    height: 6rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.head_list {
    list-style: none;
    display: flex;
    justify-content: flex-end;
    padding-inline: 1rem;
    font-size: .7rem;
}

li {
    padding-inline: 1rem;
}

img {
    width: 6%;
    margin: 0 0 0 -123px;
}
</style>