<script lang="ts">
    import Footer from "../components/Footer.svelte";
	import Header from "../components/Header.svelte";
</script>	

<Header/>

<main>
	<slot/>
</main>

<Footer/>

<style lang="scss">
	@import '../globals.css';
	@import '../animations.css';

	:global(body) {
		font-family: 'Minecraftia';
		margin: 0;
		padding: 0;
		overflow: hidden;
	}
	:root {
		background-image: url('/spruce-planks.png');
		background-position: center top;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        overflow-x: hidden;
        background-size: 40%;
        -ms-interpolation-mode: nearest-neighbor;
        /* Firefox */
        image-rendering: crisp-edges;
        /* Chromium + Safari */
        image-rendering: pixelated;
        height: auto;
        color: aliceblue;
	}
</style>