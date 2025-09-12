<script>
    import { page } from '$app/state';
    import { base } from '$app/paths';
</script>

<div id="nav">
    <div id="nav-content">
        <a class:active={page.url.pathname === base + "/"} id="nav-item" href="{base}/">Home</a>
        <a class:active={page.url.pathname === base + "/learn"} id="nav-item" href="{base}/learn">Learn More</a>
        <a class:active={page.url.pathname === base + "/about"} id="nav-item" href="{base}/about">About Us</a>
    </div>
</div>

<style>

    #nav {
        margin-top: 2%;
        display: flex;
        justify-self: center;
        flex-direction: column;
    }

    #nav-content {
        margin-top: 1%;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        gap: 3rem;
        .active {
            background-color: #7c3aed;
            color: #F9A825;
            scale: 95%;
        }

    }

    #nav-item {
        padding: 0.8rem;
        background-color: #F9A825;
        border-radius: 100vw;
        color: #7c3aed;
        transition: 0.3s linear all;
        font-family: 'Montserrat', sans-serif;
        font-weight: 600;
        text-decoration: none;
        &:hover {
            background-color: #7c3aed;
            scale: 98%;
            color: #F9A825;
        }
        &:active {
            scale: 95%;
        }
    }
</style>