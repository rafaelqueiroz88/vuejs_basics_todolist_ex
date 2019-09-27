<template>
    <nav>
        <ul>
            <li>
                <a href="#">HOME</a>
            </li>
            <li>
                <a href="#">TODO List</a>
            </li>
            <li>
                <a href="#">ABOUT</a>
            </li>
        </ul>
    </nav>
</template>

<script>
    export default {
        name: "Menu"
    }
</script>

<style scoped>
    ul {
        padding-top: 30px;
        margin-bottom: 30px;
    }
    ul li {
        margin-left: 30px;
        display: inline;
        margin-right: 10px;
    }
</style>