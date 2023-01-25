<div class="return-box">
<a href="/about" class="return">Return</a>
</div>
<div id="menu">
    <div id="menu-items">
        <h1 class="menu-text">My trophies:</h1>
        <p class="menu-text title">Zerodays CTF - June 2022</p>
        <p class="menu-text">I had the honor of serving as the leader of the winning team in the world's largest on-site cyber security competition for individuals under the age of 18.
            <br/>Through diligent effort and strategic problem-solving, I was able to secure the highest number of points from the Capture the Flag (CTF) challenges among all team members.
            <br/>The experience was incredibly rewarding and enjoyable for all involved, and I eagerly anticipate the opportunity to participate in future competitions of this caliber.</p>
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

    .title {
        color: #b6b6b6 !important;
    }

    #menu{
        height: 100vh;
        display: flex;
        align-items: center;
    }
    p.menu-text {
        font-size: clamp(.7rem, 1.8vw, 1.8rem);
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
        padding-right: 20vw;
    }
</style>
