<script>
</script>

<svelte:head>
    <title>Squid Game - about page</title>
</svelte:head>

<main>
    <div class="row">
        <div class="col2">
            <aside>

                Squid Game is a South Korean survival drama television series created by Hwang Dong-hyuk for Netflix.
            </aside>
        </div>

        <div class="col2">
            <img src="images/game2.jpg" alt="the game">
        </div>
    </div>


    <div class="row">
        <div class="col3">
            <img src="images/gamemaster.jpg" alt="game master">
        </div>

        <div class="col3">

            <h3>
                THE PLOT
            </h3>
            <p>
                The series revolves around a contest where 456 players, all of whom are in deep financial
                hardship, risk their lives to play a series of deadly children's games for the chance to win a ₩45.6
                billion (US$35 million, €33 million, or £29 million as of broadcast) prize.

            </p>
        </div>

        <div class="col3">
            <img src="images/goldmasks.jpg" alt="gold masks">
        </div>

    </div>



    <div class="row">

        <div class="col3">

            <h3>
                THE IDEA
            </h3>
            <p>
                The title of the series draws from a similarly named Korean children's game. Hwang had
                conceived of the idea based on his own economic struggles early in life, as well as the class
                disparity in South Korea and capitalism. Though he had initially written it in 2009, he was unable
                to find a production company to fund the idea until Netflix took an interest around 2019 as part of
                their drive to expand their foreign programming oﬀerings.
            </p>
        </div>
        <div class="col3">
            <img src="images/Oh_Il-nam.jpg" alt="Oh_Il-nam">
        </div>


        <div class="col3">

            <h3>
                RELEASE
            </h3>
            <p>
                Squid Game was released worldwide on September 17, 2021, to critical acclaim and international
                attention. It is Netflix's most-watched series, becoming the top-viewed program in 94 countries
                and attracting more than 142 million member households and amassing 1.65 billion viewing hours
                during its first four weeks from launch, surpassing Bridgerton for the title of most watched show.
            </p>
        </div>

    </div>



    <div class="row">
        <div class="col3">
            <img src="images/SeongGi-hun.jpg" alt="SeongGi-hun">
        </div>

        <div class="col3">

            <h3>
                RECOGNITION
            </h3>
            <p>
                The series has also received numerous accolades, including the Golden Globe Award for Best
                Supporting Actor – Series, Miniseries or Television Film for O Yeong-su and the Screen Actors
                Guild Award for Outstanding Performance by a Male Actor in a Drama Series and Outstanding
                Performance by a Female Actor in a Drama Series for Lee Jung-jae and HoYeon Jung,
                respectively, with all three making history as the first Korean actors to win in those categories.

            </p>
        </div>

        <div class="col3">
            <img src="images/HoYeonJung.jpg" alt="HoYeonJung">
        </div>

    </div>


</main>








<style>
    .row {
        display: flex;
        margin-top: 1rem;
    }

    .row img {
        display: block;
    }

    .col2 {
        width: 50%;
        text-align: justify;
    }

    .col3 {
        width: 33.33%;
        text-align: justify;


    }

    .col2 aside {
        font-family: "Megrim", system-ui;
        font-weight: 400;
        font-style: normal;

        font-size: 2.5cqw;
        padding: 2rem;


    }



    .col4 {
        width: 25%;
        padding: 0.2rem;
        text-align: justify;
    }

    .col3 h3 {
        letter-spacing: 0.4rem;

        font-family: "Megrim", system-ui;
        font-weight: 400;
        font-style: normal;

        text-align: center;

        font-size: 2cqw;
    }

    .col3 p {
        font-family: "Lato", sans-serif;
        font-weight: 400;
        font-style: normal;

        line-height: 1.7em;

        font-size: 1.2cqw;
        padding: 0 1.5rem;
    }

    .col4 p, .col4 h3 {
        padding: 0 1.5rem;
        font-size: 1cqw;
    }

    .rounded_left {
        border-radius: 20% 0 0 20%;
    }


    .rounded_right {
        border-radius: 0 20% 20% 0;
    }
</style>