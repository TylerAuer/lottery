<script lang="ts">
    const megaMillionsUrl = 'https://en.wikipedia.org/wiki/Mega_Millions'
</script>

<main>
    <h1 class="title">Lotteries</h1>
    <div class="subtitle">Are you feeling lucky?!</div>
    <p>
        You've probably heard of a lottery. Maybe you've even purchased a
        ticket. So, how do they work?
    </p>
    <p>
        First, it's important to know that there are all sorts of different
        types of lotteries. Scratch off tickets, BINGO, and McDonalds Monopoly
        games are all essentially lotteries. The essential features are that
        they are games of chance in which little or no skill is involved. And,
        they offer the chance to win very large prizes for small price.
    </p>
    <p>
        For many people, playing the lottery is fun -- though, gambling of all
        kinds can be addictive and dangerous. Let's try out a simple lottery.
    </p>
    <p>
        One very popular lottery game is
        <a href={megaMillionsUrl}>Mega-Millions</a>, which is offered in most US
        states.
    </p>
</main>

<style>
    main {
        padding: 1em;
        max-width: 800px;
        margin: 0 auto;
    }

    .title {
        text-align: center;
        color: #333;
        text-transform: uppercase;
        font-size: 3rem;
        font-weight: 300;
    }

    .subtitle {
        text-align: center;
        color: black;
        font-weight: bold;
    }

    @media (max-width: 640px) {
        main {
            max-width: none;
        }
    }
</style>
