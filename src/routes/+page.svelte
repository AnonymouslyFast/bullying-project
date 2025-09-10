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


<style>
    @import './main.css'; /* background */

    #title-container {
        width: 60%;
        justify-self: center;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        margin-top: 3%;
        border-radius: 2vw;

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
            font-weight: 700; /* bold for impact */
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

        justify-self: right;
        rotate: 10deg;

    }
</style>