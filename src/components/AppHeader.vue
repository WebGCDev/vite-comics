<script>
export default {};
</script>

<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="">
        <ul class="head_list">
            <li>CHARACTER</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>
    </header>
</template>

<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;

header {
    background-color: white;
    height: 6rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 2rem;

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
    padding-left: 1rem;
}</style>