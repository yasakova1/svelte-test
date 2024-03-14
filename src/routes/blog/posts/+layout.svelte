<div class="container">
    <a href="/blog">Назад</a>
    <slot />
</div>

<style>
    .container {
    margin: 50px auto;
    max-width: 800px;
    padding: 0 20px; }
    .container a {
        cursor: pointer;
        color: rgb(18, 18, 18);
        position: relative;
        left: -90px;
    }
</style>
