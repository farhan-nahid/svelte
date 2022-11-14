<script>
    // export let name;
    const num = 0;
</script>

<style>
    main {
        text-align: center;
        padding: 1em;
        max-width: 240px;
        margin: 0 auto;
    }

    h1 {
        color: #ff3e00;
        text-transform: uppercase;
        font-size: 4em;
        font-weight: 100;
    }

    @media (min-width: 640px) {
        main {
            max-width: none;
        }
    }
</style>

<main>
    <h4>Number {num}</h4>
    {#if num === 0}
        <h1>Number is zero</h1>
    {:else if num < 0}
        <h1>Number is Negetive</h1>
    {:else if num > 0}
        <h1>Number is Positive</h1>
    {:else}
        <h1>This is not a number</h1>
    {/if}
</main>
