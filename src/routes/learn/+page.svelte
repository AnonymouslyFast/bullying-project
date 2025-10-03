<script>
    import Navbar from "$lib/Navbar.svelte";
</script>


<div class="container">
    <Navbar />

    <div id="title-container">
        <div id="title-content">
            <div id="title">
                <h1>Learn More</h1>
                <p>
                    Bullying has been a constant in schools for a long time, so we've decided to compile
                    the most popular bullying types and define them.
                </p>
            </div>
        </div>
    </div>

    <div id="nav">
        <div id="nav-content">
            <a id="nav-item" href="#Cyber">Cyber</a>
            <a id="nav-item" href="#physical">Physical</a>
            <a id="nav-item" href="#verbal">Verbal</a>
        </div>
    </div>

    <section id="cyber">
        <div class="content">
            <a href="#cyber"><h4>Cyber Bullying</h4></a>
            <div class="container-column">
                <p>
                    Cyber bullying refers to bullying someone through the internet using a computer device. Some examples of
                    these include sending hateful messages, or spreading rumors over social media sites. This
                    is an extremely common form of bullying since the rise of technology and is not taken seriously enough.
                    To combat this activity from your or someone else's messaging, report the user, and talk to a trusted adult.
                </p>
                <img src="Cyber.jpg" alt="phone on social media.">
            </div>
        </div>
    </section>

    <section id="physical">
        <div class="content">
            <a href="#physical"><h4>Physical Bullying</h4></a>
            <div class="container-column">
                <p>
                    Physical bullying refers to the act of physical contact to bully someone. This includes fighting, pushing,
                    or any other form of non-consensual contact to the person. It's one of the worse types of bullying, since
                    it's physically hurting the victim and can kill people. If you or someone you know is experiencing this
                    type of bullying, tell a trusted adult, and try to defuse the situation as best you can.
                </p>
                <img src="Physical.jpg" alt="fist punching a wall.">
            </div>
        </div>
    </section>

    <section id="verbal">
        <div class="content">
            <a href="#verbal"><h4>Verbal Bullying</h4></a>
            <div class="container-column">
                <p>
                    Verbal bullying refers to bullying someone through words. This includes name calling, spreading rumors, and
                    any other use of words to spread hate towards another individual. This type of bullying can cause someone to
                    have anxiety, and even sometimes depression. If you or someone you know is experiencing this, please tell
                    a trusted adult, and get away from these situations as best you can.
                </p>
                <img src="Verbal.png" alt="woman yelling.">
            </div>
        </div>
    </section>
</div>


<div style="margin-top: 5%;" id="copyright">
    <p>© 2025 <a href="./about#team">Group 1</a>. All rights reserved.</p>
</div>

<style>
    @import "../main.css";
    @import "./mobile.css";

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

    section {
        margin-top: 5%;
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
            font-size: 2rem;
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
            font-size: 1.5rem;
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
</style>