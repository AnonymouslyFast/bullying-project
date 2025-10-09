<script>
    import Navbar from "$lib/Navbar.svelte";
</script>


<div class="container">
    <Navbar />

    <div id="title-container">
        <div id="title-content">
            <div id="title">
                <h1>Hoodie Information</h1>
                <p>

                </p>
            </div>
        </div>
    </div>


</div>


<div style="margin-top: 5%;" id="copyright">
    <p>© 2025 <a href="./about#team">Group 1</a>. All rights reserved.</p>
</div>

<style>
    @import "../main.css";


    #title-container {
        width: 40%;
        justify-self: center;
        display: flex;
        margin-top: 3%;

        border-bottom: 1px solid #cccccc;
        padding-bottom: 1%;
        color: #cccccc;
    }

    #title-content {
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        text-align: center;
        gap: 5rem;
        flex-wrap: nowrap;
    }

    #title {
        width: fit-content;
        h1 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            font-size: 2.5rem;
            color: #FFFFFF;
        }

        p {
            width: 70%;
            justify-self: center;
            margin: 0 auto;
            font-family: 'Montserrat', sans-serif;
            font-weight: 600;
            font-size: 1.3rem;
            color: #F9A825;
        }
    }


</style>