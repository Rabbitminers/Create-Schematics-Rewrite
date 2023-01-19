<script lang="ts">
    import Home from "../components/Home.svelte";
    import DATA from "../data/data";

    let width;
</script>

<home bind:clientWidth={width}>
    <Home/>
    {#if DATA.MOBILE_DEVICE_WIDTH < width}
        Hello world
    {/if}
</home>

<style lang="scss">
    home {
        display: flex;
        flex-direction: row;
    }
</style>