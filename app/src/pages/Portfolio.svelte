<script>
    import {link} from 'svelte-spa-router';
    </script>

<main>

    <h1>Portfolio</h1>
    <section class="project_section">
        <div class="project_div">
            <h2>Blablabook</h2>
            <img src="./images/Home_blablabook.png" alt="homepage blablabook" class="blabla_image" width="55%">
            <div class="presentation_project">
            <p>Projet de fin d'études, Blablabook est une plateforme en ligne destinée aux amateurs-rices de suivre leurs lectures, de découvrir de nouveaux livres et de partager leurs opinions avec d'autres lecteurs-rices.</p>
            </div>
            <a href="/project/1" target="blank" use:link><button>Voir plus</button></a>
        </div>
    </section>
</main>

<style>
    
     main {
        margin: 60px 30px;
        width: 80%;
        padding: 10px 10px;
    }
    .project_div {
        border: var(--bluemoon) solid 1px;
        padding: 10px 10px;
        text-align: center;
        margin-top: 70px;
    }
      h1 {
        font-size: 35px;
        text-align: center;
        
    }
    h2 {
        margin-top: 40px;
    }
    p {
        margin: 20% 0%;
    }
    img {
        margin-top: 20%;
    }
    button {
        width: 100px;
        height: 30px;
        border-radius: 50px;
        background-color: transparent;
        color: var(--white);
        border: none;
        cursor: pointer;
        margin-bottom: 30px;
        font-size: 20px;
    }
    button:hover {
        background-color: var(--bluemoon);
    color: var(--black_background);
    transition: ease-in-out 0.3s all;
    }

                /* ******* Desktop ******* */
@media screen and (min-width: 1024px) { 

    h1 {
        font-size : 55px;
    }

    h2 {
        font-size: 40px;
    }
   .blabla_image {
    margin-top: 10%;
   }
    main {
        margin:8% 10%;
    }
    .presentation_project {
        width: 60%;
        margin-left: 5%;
        text-align: left;
    }
    p {
        font-size: 30px;
    }

    button {
        font-size: 30px;
        width: 130px;
    }
}

</style>