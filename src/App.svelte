<script>
    let nombre = 'Makros'
    const nombre_2 = 'Sandre'
    nombre = "<strong style='color: firebrick'>Pedro</strong>"
	const url = "https://api.com"
</script>

<main>
    <p>{@html nombre}</p>
</main>

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

    h2 {
        color: red;
    }

    @media (min-width: 640px) {
        main {
            max-width: none;
        }
    }
</style>