<div id="menu">
    <div id="menu-items">
    <h1 class="menu-text">Hi, I'm Kai.</h1>
        <a href="/about" class="menu-item">Learn More?</a>
    </div>
</div>


<style>

    #menu{
        height: 100vh;
        display: flex;
        align-items: center;
    }
    .menu-text {
        font-size: clamp(3rem, 9vw, 9rem);
        color: white;
        font-family: "Ibarra Real Nova", serif;

        display: block;
        text-decoration: none;
        padding: clamp(0.11rem, 0.5vw, 1rem) 0;
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
        font-size: clamp(1rem, 6vw, 6rem);
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
