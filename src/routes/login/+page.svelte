<script lang="ts">
    import DATA from "../../data/data";
    // TODO; Implement Firebase Auth On Load
    let width;

    let username: string;
    let password: string;
</script>


<div class='login-wrapper' bind:clientWidth={width}>
    <div class='form-wrapper'>
        <form class="login-form">
            <h1>Login</h1>
            <hr/>

            <input
                bind:value={username}
                type="text"
                placeholder="Email..."
            />

            <input
                bind:value={password}
                type="text"
                placeholder="Password..."
            />
            
            <button>Submit</button>
        </form>
    </div>

    {#if DATA.MOBILE_DEVICE_WIDTH < width}
        <img class="login-image" alt='banner' src='/home/banner-image.jpeg'>
    {/if}
</div>


<style lang="scss">
    .login-wrapper {
        display: flex;
        flex-direction: row;
        height: max-content;
    }

    .form-wrapper {
        width: 30%;
        box-shadow: 10px 10px black;
    }

    .login-image {
        width: 70%;
    }

    .login-form {
        color: black;
        border-style: solid;
        background-color: var(--white);
        border-color: black;
        border-radius: 20px;
        height: auto;
        gap: 20px;
        padding: 10px;
        width: 80%;
        margin: auto;

        > input[type="text"] {
            color: aliceblue;
            font-family: 'Minecraftia';
            background-color: var(--primary);
            border-style: solid;
            border-color: var(--white);
            border-radius: 10px;
            padding: 10px;
        }

        > input[type="text"]::placeholder {
            color: var(--grey);
        }
    }

    @media only screen and (max-width: 800px) { .form-wrapper {
        width: 100%;
    }}
</style>