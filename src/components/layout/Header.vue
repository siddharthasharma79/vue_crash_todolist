<template>
    <header class="header">
        <h1>TodoList</h1>
        <div id="nav">
            <router-link to="/">Home</router-link> | &nbsp;
            <router-link to="/about">About</router-link>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>
    .header {
        background: #333;
        color: #5fb709;
        text-align: center;
        padding: 10px;
    }

    .header a {
        color: #fff;
        padding-right: 10px;
        text-decoration: none;
    }
</style>

