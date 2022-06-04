<script context="module">
    import { browser, dev } from '$app/env';

    // we don't need any JS on this page, though we'll load
    // it in dev so that we get hot module replacement...
    export const hydrate = dev;

    // ...but if the client-side router is already loaded
    // (i.e. we came here from elsewhere in the app), use it
    export const router = browser;

    // since there's no dynamic data here, we can prerender
    // it so that it gets served as a static asset in prod
    export const prerender = true;
</script>

<svelte:head>
    <title>About</title>
    <meta name="description" content="About this app" />
</svelte:head>

<div class="content">
    <h1>The Venue ~</h1>

    <figure>
        <img src="exampleImage.png" alt="a nice old house">
    </figure>

    <p>
        The <a href="/todos">TODOs</a> page illustrates SvelteKit's data loading and form handling. Try using
        it with JavaScript disabled!
    </p>
</div>

<style>
    img {
        max-width: 100%;
    }
    .content {
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
</style>
