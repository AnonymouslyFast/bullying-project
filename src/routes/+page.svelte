<script>
</script>



<div id="title-container">
    <div id="title-content">
        <div id="title">
            <h1>Stop<br>Bullying<br>Together!</h1>
            <p>Kindness is strength.<br>Bullying is weakness.</p>
        </div>
        <img id="shirt-img" src="shirt.png" alt="test shirt">
    </div>
</div>


<div id="nav">
    <div id="nav-content">
        <a id="nav-item" href="learn/">Learn More</a>
        <a id="nav-item" href="about/">About Us</a>
    </div>
</div>


<div id="copyright">
    <p>© 2025 <a href="./about#team">Group 1</a>. All rights reserved.</p>
</div>

<style>
    @import './main.css'; /* background */
    @import './mobile.css';

    #copyright{
        position: absolute !important;

    }


    #title-container {
        width: 60%;
        justify-self: center;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        margin-top: 6%;

        border-bottom: 1px solid #cccccc;
        padding-bottom: 1%;
        color: #cccccc;
    }

    #title-content {
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: center;
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
            font-family: 'Montserrat', sans-serif;
            font-weight: 600;
            font-size: 1.3rem;
            color: #F9A825;
        }
    }

    #shirt-img {
        max-width: 35%;
        object-fit: scale-down;
        aspect-ratio: 1/.8;

        justify-self: right;
        rotate: 10deg;
    }

    #nav {
        margin-top: 2%;
        display: flex;
        justify-self: center;
        flex-direction: column;
    }

    #nav-content {
        width: 100%;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        gap: 3rem;
    }

    #nav-item {
        padding: 0.7rem;
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