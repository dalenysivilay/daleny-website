<template>
<nav>
    <p class="logo">Daleny Sivilay</p>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/blog">Blog</a></li>
        <li><a href="/projects">Projects</a></li>
        <li><a href="/tools">Tools</a></li>
    </ul>
</nav>
</template>
<script>
export default {
}
</script>
<style lang="scss" scoped>
@import '~assets/_variables.scss';

nav {
    width: 100%;
    display: flex;
    flex-direction: row;
    vertical-align: center;
    justify-content: space-between;
    margin: 0;
    padding: 0 64px 0 64px;
    background-color: $primary-color;
}

.logo {
    display: inline-block;
    vertical-align: top;
    margin: 0;
    padding: 0;
    color: white;
}

ul {
    list-style-type: none;
    vertical-align: center;
    margin: 0;
    padding: 0;
}

li {
    display: inline-block;
}

a {
    text-decoration: none;
    color: white;
}
</style>