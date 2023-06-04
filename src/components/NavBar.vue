<template>
    <header>
        <img alt="Vue logo" class="logo" src="src/assets/logo.png">
        <nav>
            <ul class="nav_links">
                <li><a href="#">Home</a></li>
                <li><a href="#">Men Section</a></li>
                <li><a href="#">Women Section</a></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'NavBar',
    props: {}
}
</script>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
li, a {
    font-family: "Inter", sans-serif;
    color:#2c3e50;
    font-weight: 600;
    text-decoration: none;
}

header {
    filter: drop-shadow(0mm -6mm 6mm #030303);
    margin: 0px;
    background-color: rgb(239, 238, 255);
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 10%;
    max-height: 60px;
}

.logo {
    width: auto;
    height: auto;
}

.nav_links {
    list-style: none;
}

.nav_links li {
    display: inline-block;
    padding: 0px 20px;
}

.nav_links li a {
    transition: all 0.3s ease 0s;
}

.nav_links li a:hover {
    color: #2866eb;
}
</style>