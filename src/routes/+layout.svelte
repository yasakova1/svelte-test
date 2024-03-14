<script>
    const nav = [
        { title: "Главная", href: "../", isShow: true },
        { title: "Блог", href: "/blog", isShow: true },
        { title: "Портфолио", href: "/project", isShow: true },
        { title: "Контакты", href: "/contact", isShow: true },
        { title: "temp", href: "/temp", isShow: false },
    ];
</script>

<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Анна Тайнби</a>
        <div id="frame"> <iframe style="border: none" width="200" height="200" src="https://rive.app/community/4994-10102-hippo/embed" allowfullscreen></iframe> </div>
        <div class="nav-links">
            {#each nav as link}
                {#if link.isShow}
                    <a href={link.href} class="link">{link.title}</a>
                {/if}
            {/each}
        </div>
    </div>
</nav>
<div class="container">
    <slot />
</div>

<style>
    .container {
        max-width: 1400px;
        margin: 50px auto;
    }
</style>
