<template>
<header class="container">
    <a href="/">
    <img src="../assets/dc-logo.png" alt="dc-logo.png">
    </a>
    <nav>
        <ul>
            <li>
                <a href="/characters">CHARACTERS</a>
            </li>
             <li>
                <a href="/comics">COMICS</a>
            </li>
             <li>
                <a href="/movies">MOVIES</a>
            </li>
             <li>
                <a href="/tv">TV</a>
            </li>
             <li>
                <a href="/games">GAMES</a>
            </li>
             <li>
                <a href="/collectibles">COLLECTIBLES</a>
            </li>
             <li>
                <a href="/videos">VIDEOS</a>
            </li>
             <li>
                <a href="/fans">FANS</a>
            </li>
             <li>
                <a href="/news">NEWS</a>
            </li>
             <li>
                <a href="/shop">SHOP</a>
            </li>
        </ul>
    </nav>
</header>
</template>

<script>
export default {
name: 'Header',
}
</script>

<style scoped lang="scss">
header {
    display: flex;
   justify-content: space-between;
}
ul {
    display: flex;
    list-style: none;
    margin: 1.6rem 0 ;
}
a {
    display: inline-block;
    padding: 1rem;
    text-decoration: none;
    font-weight: 501;
    font-size: 12px;
    color: black;
    &.active,
    &:hover {
        color: blue;
    }
    img {
        width: 60px;
    }

}

</style>