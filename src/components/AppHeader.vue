<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <header>
        <div class="logo">
            <img src="/img-general/img/dc-logo.png" alt="Logo DC">
        </div>
        <nav>
            <ul class="top-menu">
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#" class="underlined">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </nav>
    </header>
</template>



<style scoped>
header {
    display: flex;
    
    align-items: center;
    justify-content: space-between;
    padding: 10px 12rem;
    background-color: white;
    & .logo {
        width: 100%;
    }
    & ul {
        gap: 20px;
        list-style: none;
        display: flex;
        & li {
            margin-right: 20px;
            & a {
                text-decoration: none;
                font-size: smaller;
                font-weight: bold;
                color: var(--menu-text);
            }
            & a.underlined{
                color: var(--menu-active);
                text-decoration: none;
                border-bottom: 5px solid var(--menu-active);
                padding-bottom: 50px;
            }
        }
    }
}
</style>