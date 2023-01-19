<script lang="ts">
    import Home from "../components/Home.svelte";
    import DATA from "../data/data";

    let width;
</script>

<home bind:clientWidth={width}>
    <Home/>
    {#if DATA.MOBILE_DEVICE_WIDTH < width}
        <img class="image-banner" src='/home/train.webp' alt='banner'>
    {/if}
</home>

<style lang="scss">
    home {
        display: flex;
        flex-direction: row;
    }

    .image-banner {
        flex-grow: 1;
    }
</style>