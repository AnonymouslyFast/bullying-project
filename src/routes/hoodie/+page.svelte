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
                    Our physical product is a hoodie, it will help spread the message our group is advocating for.
                </p>
            </div>
        </div>
    </div>

    <section id="about">
        <div class="content">
            <h4>Background</h4>
            <div class="container-column">
                <p>
                    The hoodie's color is purple since it stands out more, we put the phrase "hear see no evil" referencing the
                    three wise monkeys in a popular folk tale. On the back we put a hand symbol with inspirational things that
                    will hopefully make someone's day when reading it. There's also the a inspirational saying on the back about
                    God, hoping to spread his gospel and make people turn to the light.
                </p>
                <img src="Hoodie-F&B.png" alt="Hoodie front and back" />
            </div>
        </div>
    </section>

    <div id="bottom-container">
        <div id="bottom-content">
            <div id="item">
                <h4>Contact Us!</h4>
                <p>Have any questions? <br> contact us!</p>
                <a href="mailto:bully@anonymouslyfast.com">bullying@anonymouslyfast.com</a>
            </div>
            <div id="item">
                <h4>Credit</h4>
                <p>Credit to the one who designed this!</p>
                <p id="credit">Damariah Ceasar</p>
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

    section {
        margin-top: 3%;
        padding: 2rem;
        display: flex;
        justify-self: center;
        flex-direction: column;
        border-radius: 2vw;
        width: 60%;
        box-shadow:
                rgba(204, 204, 204, 0.2) 0 0 0 1px inset,
                rgba(204, 204, 204, 0.9) 0   0 0 1px;
        .content {
            h4 {
                font-family: 'Montserrat', sans-serif;
                font-weight: 600;
                font-size: 1.8rem;
                color: #FFFFFF;
                margin: 0;
                border-bottom: 3px solid #cccccc;
                padding-bottom: 1%;
                width: fit-content;

            }

            p {
                color: #cccccc;
                font-family: 'Poppins', sans-serif;
                font-weight: lighter;
                font-size: 1.3rem;
                max-width: 60%;
                width: fit-content;
            }
            a {
                text-decoration: none;
                transition: 0.3s linear all;
            }
        }

    }

    .container-column {
        display: inline-flex !important;
        flex-direction: row;
        gap: 2rem;
        width: 100%;
        height: 100%;

        img {
            width: 30%;
            border-radius: 2vw;
            object-fit: cover;
        }
    }

    #bottom-container {
        width: 60%;
        display: flex;
        flex-direction: column;
    }

    #bottom-content {
        width: 100%;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        margin-top: 5%;
        gap: 1rem;
    }

    #item {
        border-radius: 2vw;
        box-shadow:
                rgba(204, 204, 204, 0.2) 0 0 0 1px inset,
                rgba(204, 204, 204, 0.9) 0   0 0 1px;
        width: 45%;
        padding: 2%;
        h4 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 600;
            font-size: 1.5rem;
            color: #FFFFFF;
            margin: 0;
            border-bottom: 3px solid #cccccc;
            padding-bottom: 1%;
            width: fit-content;
            justify-self: center;

        }

        p {
            color: #cccccc;
            font-family: 'Poppins', sans-serif;
            font-weight: lighter;
            font-size: 1.3rem;
            max-width: 85%;
            width: fit-content;
            justify-self: center;
            text-align: center;
        }
        a {
            display: flex;
            justify-self: center;
            text-align: center;
            text-decoration: none;
            transition: 0.3s linear all;
            font-size: 1.3rem;
            color: #7c3aed;
        }
        #credit {
            color: #F9A825;
        }
    }


</style>