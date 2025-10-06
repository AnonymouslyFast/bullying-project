<script>
    import { page } from '$app/state';
    import { base } from '$app/paths';
</script>

<div id="nav">
    <div id="nav-content">
        <a class:active={page.url.pathname === base + "/"} id="nav-item" href="{base}/">Home</a>
        <a class:active={page.url.pathname === base + "/learn"} id="nav-item" href="{base}/learn">Learn More</a>
        <a class:active={page.url.pathname === base + "/hoodie"} id="nav-item" href="{base}/hoodie">Hoodie Info</a>
        <a class:active={page.url.pathname === base + "/about"} id="nav-item" href="{base}/about">About Us</a>
    </div>
</div>

<style>

    #nav {
        margin-top: 2%;
        margin-bottom: 0;
        margin-left: 2%;
        width: fit-content;
        padding: 0;
        display: flex;
        justify-self: left;
        flex-direction: column;
    }

    #nav-content {
        margin-top: 1%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        .active {
            background-color: #7c3aed;
            color: #F9A825;
            scale: 95%;
        }

    }

    #nav-item {
        transition: 0.3s linear all;
        font-family: 'Montserrat', sans-serif;
        font-weight: 600;
        text-decoration: none;
        color: #F9A825;
        text-align: center;
        background-color: initial !important;
        &:hover {

        }
        &:active {
            border: 5px solid #cccccc !important;
        }
    }

    @media (max-width: 800px) {
        #nav-content {
            width: 100% !important;
            gap: 1.5rem !important;
        }
    }
</style>