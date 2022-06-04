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
    <h1>Schedule</h1>

    

    <div class="grid">

        <div class="grid-item">
            <span class="header">•</span>
        </div>
        <div class="grid-item">
            <span class="header">Saturday</span>
        </div>
        <div class="grid-item">
            <span class="header">Sunday</span>
        </div>
        <div class="grid-item">
            <span class="header">Sunday</span>
        </div>
<!--=====================Row==================-->
        <div class="grid-item time">
            8:30
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
<!--=====================Row==================-->
        <div class="grid-item time">
            9:00
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
<!--=====================Row==================-->
        <div class="grid-item time">
            9:30
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
<!--=====================Row==================-->
        <div class="grid-item time">
            10:00
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
<!--=====================Row==================-->
        <div class="grid-item time">
            10:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            10:30
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            11:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            11:30
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            11:45
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            12:00
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            13:00
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            14:00
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            14:30
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            14:45
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:00
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <!--=====================Row==================-->
        <div class="grid-item time">
            15:15
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
        <div class="grid-item">
            asdf
        </div>
    </div>
</div>

<style>

    .content {
        width: 100%;
        padding: 0rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .grid {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        grid-auto-flow: row;
        word-break: break-all;
        width: 90%;

    }
    .grid-item {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        flex-basis: 1; 
        padding-top: .15rem;
        border-bottom: dashed 1px;
    }
    .header, .time {
        font-weight: bold;
    }
   
    

    .grid {
        color: var(--heading-color);
    }
</style>
