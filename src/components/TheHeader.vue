<template>
    <header class="header">
            <h1>Museum Project</h1>
        <nav class="nav">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">bliblablu</a></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'TheHeader',
};
</script>

<style scoped>
.header {
    background-color: #f0f0f0;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 50px;
    height: 50px;
    margin-right: 10px;
}

.nav ul {
    list-style: none;
    display: flex;
    align-items: center;
}

.nav li {
    margin-right: 10px;
}

.nav a {
    text-decoration: none;
    color: #333;
}

.nav a:hover {
    color: #000;
}
</style>
