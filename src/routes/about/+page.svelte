<div class="return-box">
    <a href="/" class="return">Return</a>
</div>
<div id="menu">
    <div id="menu-items">
        <h1 class="menu-text">Would you like to see</h1>
        <a href="/professional" class="menu-item">professional stuff</a>
        <h1 class="menu-text">or</h1>
        <a href="/fun" class="menu-item">fun stuff?</a>
    </div>
</div>


<style>

    .return-box {
        margin-right: 0;
        margin-left: auto;
        display:flex;

    }

    .return {
        color: white;
        display: block;
        margin-left: auto;
        padding-top: clamp(1vw, 2vw, 4vw);
        padding-right: clamp(1vw, 2vw, 4vw);
    }

    #menu{
        height: 100vh;
        display: flex;
        align-items: center;
    }
    .menu-text {
        font-size: clamp(2rem, 6vw, 6rem);
        color: white;
        font-family: "Ibarra Real Nova", serif;

        display: block;
        text-decoration: none;
    }

    .menu-item:hover {
        background-position: -100%;
    }



    .menu-item {
        background: linear-gradient(to right, #CCCCCC 50%, #FF5858 50%, #CC2E5D);
        background-size: 200%;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        transition: .7s ease-in-out;
        font-size: clamp(1rem, 4vw, 4rem);
        color: white;

        font-family: "Ibarra Real Nova", serif;

        display: block;
        text-decoration: none;
        padding: clamp(0.25rem, 0.5vw, 1rem) 0;
    }

    #menu-items {
        margin-left: clamp(2rem, 10vw, 48rem);
    }
</style>
