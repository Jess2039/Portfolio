<script>
    import {link} from 'svelte-spa-router';
    </script>

<main>

    <h1>Portfolio</h1>
    <section class="project_section">
        <div class="project_div">
            <h2>Blablabook</h2>
            <img src="/images/Home_blablabook.png" alt="homepage blablabook" width="55%">
            <p>Projet de fin d'études, Blablabook est une plateforme en ligne destinée aux amateurs-rices de suivre leurs lectures, de découvrir de nouveaux livres et de partager leurs opinions avec d'autres lecteurs-rices.</p>
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
        margin: 50px 0px;
    }
    img {
        margin-top: 50px;
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
    main {
        margin:8% 10%;
    }
    p {
        font-size: 20px;
    }
}

</style>