<svelte:head>
    <title>Ана Тайнби</title>
</svelte:head>
<div class="container">
    <div class="info">
        <div class="animate-background">
            <div class="container info-container">
                <div class="info-text">
                    <h1>
                        <p class="animate-text-1">ᓚᘏᗢ</p>
                        <p class="text-2">Привет!</p>
                    </h1>
                </div>
                <h2 class="subtitle">
                    Мой первый проект, использующий svelte
                </h2>
                <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
                <div style="color:black"  class="scroll-button animate-scroll" tabindex="0">
                    <div class='home-next'>
                        <a href="/blog">Click Here</a>
                        <div class="arrow">→</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="background-div"></div>

<style>
    .info {
        text-align: center;
        position: relative;
    }
    .info-container {
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: start;
        text-align: left;
    }
    .container {
        max-width: 1400px;
        margin: 100px 0 0 2.5rem;
    }
    .info h1 {
        font-size: 4rem;
        margin-bottom: 20px;
    }
    .info h1 p {
        position: relative;
        font: inherit;
        margin: 0;
        text-align: left;
        line-height: 130%;
        width: fit-content;
        font-weight: 800;
        letter-spacing: -0.03em;
    }
    .info h2 {
        max-width: 65ch;
        font-weight: 200;
        margin-top: 0.5rem;
    }
    .background-div {
        background-color: rgba(201, 201, 201, 0.696);;
        border: 1px solid rgba(103, 103, 103, 0.397);
        width: 100%;
        border-top-right-radius: 80px;
  border-bottom-left-radius: 80px;
        height: 56vh;
        margin: -205px auto;
    }
    .info .info-text {
        position: relative;
    }
    .scroll-button {
        display: flex;
        border: none;
        outline: none;
        cursor: pointer;
    }
    .scroll-button .arrow {
        margin-left: 0.5rem;
    }
    .home-next a{
        color: rgb(65, 65, 65);
    }
    .home-next:hover {
        cursor: pointer;
        font-weight: 800;
        color: rgb(65, 65, 65);
    }
</style>
