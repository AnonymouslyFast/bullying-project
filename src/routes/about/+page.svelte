<script lang="ts">
    import Navbar from "$lib/Navbar.svelte";
</script>

<div class="container">
    <Navbar />
    <div id="title-container">
        <div id="title-content">
            <div id="title">
                <h1>About Us</h1>
                <p>
                    We are a group of four high school students from 2 different high schools that came together, and
                    are determined to make the world a better place!
                </p>
            </div>
        </div>
    </div>

    <div id="team-row">
        <section id="team">
            <div id="content">
                <h4>Meet The Team</h4>

                <div id="team-card">
                    <h5><a href="https://anonymouslyfast.com/">Caleb Shearer</a></h5>
                    <p>
                        T-shirt, design, and website.
                    </p>
                </div>

                <div  id="team-card">
                    <h5><a href="#">Damariah Ceasar</a></h5>
                    <p>
                        T-shirt, design, and research.
                    </p>
                </div>

                <div id="team-card">
                    <h5><a href="#">Ja'Qure Brown</a></h5>
                    <p>
                        T-shirt, design, and research.
                    </p>
                </div>

                <div id="team-card">
                    <h5><a href="#">Mehki Anderson</a></h5>
                    <p>
                        T-shirt, design, and research.
                    </p>
                </div>
            </div>
        </section>

        <section id="about">
            <div id="content">
                <h4>Who are we?</h4>
                <p>
                    We are a group of four high school students doing this because we want the world to be
                    a safer place. This project is to help people who might be experiencing bullying themselves,
                    or people who just want to learn more about bullying.
                </p>
            </div>
        </section>

        <section id="contact">
            <div id="content">
                <h4>Contact us!</h4>
                <a href="mailto:bullying@anonymouslyfast.com">bullying@anonymouslyfast.com</a>
            </div>
        </section>
    </div>
</div>



<div id="copyright">
    <p>© 2025 <a href="#team">Group 1</a>. All rights reserved.</p>
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
            justify-self: center;
            font-family: 'Montserrat', sans-serif;
            margin: 0 auto;
            font-weight: 600;
            font-size: 1.3rem;
            color: #F9A825;
            width: 70%;
        }
    }

    section {
        padding: 2rem;
        display: flex;
        justify-self: center;
        flex-direction: column;
        border-radius: 2vw;
        width: fit-content;
        box-shadow:
                rgba(204, 204, 204, 0.2) 0 0 0 1px inset,
                rgba(204, 204, 204, 0.9) 0 0 0 1px;

        h4 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 600;
            font-size: 2rem;
            color: #FFFFFF;
            border-bottom: 3px solid #cccccc;
            margin-top: 0;
            margin-bottom: 2rem;
            padding-bottom: 0;
            width: fit-content;
            justify-self: center;
        }

        a {
            color: #F9A825;
            transition: 0.3s linear all;

        }
        a:hover {
            color:  #7c3aed;
        }
    }

    #team-row {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        padding: 2rem;
        justify-content: center;
        gap: 3rem;
    }

    #team-card {
        display: flex;
        flex-direction: row;
        justify-self: center;
        gap: 1rem;
        width: fit-content;
        h5 {
            transition: 0.3s linear all;
            font-family: 'Montserrat', sans-serif;
            font-weight: 600;
            font-size: 1rem;
            margin-top: 0;
            padding: 0;
            color: #F9A825;
            a {
                transition: 0.3s linear all;
                text-decoration: none;
                color: #F9A825;
            }
        }
        p {
            transition: 0.3s linear all;
            font-family: 'Poppins', sans-serif;
            font-size: 1rem;
            margin: 0;
            padding: 0;
            color: #7c3aed;
        }
        &:hover {
            h5 {
                color: #7c3aed;
                a {

                    color: #7c3aed;
                }
            }
            p {

                color: #F9A825;
            }
        }

    }

    #about {
        width: 30%;
        display: flex;
        flex-direction: column;
        h4 {
            justify-self: left !important;
        }
        p {
            justify-self: left;
            width: 100%;
            text-align: left;
            font-family: 'Poppins', sans-serif;
            font-size: 1rem;
            color: #cccccc;
        }
    }


</style>