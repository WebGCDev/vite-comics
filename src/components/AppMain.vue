<script>
</script>

<template>
    <main>
        <div class="contents">
            <h2>--&gt; Content goes here &lt;--</h2>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;

main {
    background-color: #1c1c1c;
    height: 8rem;

    .contents {
        display: flex;
        flex-direction: column;
        justify-content: left;
        flex-shrink: 1;
        color: white;
        max-width: 1200px;
        margin: 0 0 0 350px;

        h2 {
            color: white;
            margin-top: 45px;

            &:hover {
                cursor: pointer;
                color: #0282f9;
            }
        }
    }
}
</style>