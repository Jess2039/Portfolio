<script>
    import { MetaTags } from 'svelte-meta-tags';
</script>
<MetaTags
title="Portfolio, Jessica JAMAIN"
description="Portfolio, Jessica JAMAIN, Développeur, Intégrateur web, Projet Svelte, Directus" />
<main>
<h1>Projet Blablabook</h1>
<div class="stack_div">
    <h3>Full-Stack</h3>
    <img src="./images/htmlcss-logo.svg" alt="html/css" width="100">
    <img src="./images/svelte-bg.png" alt="svelte" width="100">
    <img src="./images/Directus_Logo.png" alt="Directus" width="100">
</div>
<p>Projet de fin d'études, Blablabook est une plateforme en ligne destinée à aider les amateurs de lecture à gérer leur bibliothèque personnelle en enregistrant les livres qu'ils ont lus, en attribuant des notes et en laissant des avis. L'objectif principal du site est de permettre aux utilisateurs de suivre leurs lectures, de découvrir de nouveaux livres et de partager leurs opinions avec d'autres lecteurs.
   Développé en utilisant des technologies telles que Svelte, Directus, SQLLite et Figma.<br> Le projet a été conçu pour permettre aux utilisateurs de créer leur compte, se connecter à leur espace personnel, gérer sa propre bibliothèque en ajoutant des livres sur les différentes étagères, de laisser un avis sur les livres.
   La maquette du site a été créée sur Figma, l'interface a été conçue de manière responsive et une attention particulière a été apportée sur le contraste des couleurs et le code html afin de rendre le site accessible.
   L'utilisation de Svelte a permis de créer une interface utilisateur fonctionnelle. Le backend a pu être géré via Directus.
</p>
<section class="images_section">
<img src="./images/Home_blablabook.png" class="blabla_capture_home" alt="blablabook" width="90%">
<div class="images_minwidth">
<img src="./images/Mobile_menu.png" class="blabla_capture" alt="blablabook" width="40%">
<img src="./images/Mobile-discovery.png" class="blabla_capture" alt="blablabook" width="40%">
<img src="./images/book_page.png" class="book_capture" alt="blablabook" width="50%">
</div>
</section>
</main>

<style>
    main {
        margin: 50px 20px;
        width: 80%;
        border: var(--bluemoon) solid 2px;
        padding: 10px 20px;
    }
    h1 {
        font-size: 35px;
    }
    h3 {
        font-size: 20px;
    }
    .blabla_capture {
        margin: 15px 15px;
    }
    .blabla_capture_home {
        margin: 15px 15px;
    }
    .book_capture {
        margin-left: 25%;
    }

              /* ******* Desktop ******* */
@media screen and (min-width: 1024px) { 
    main {
        width: 85%;
        margin: 110px 7%;
        padding: 20px 30px;
    }
    h1 {
        font-size: 45px;
        text-align: center;
    }
    h3 {
        margin-right: 100px;
    }
    .stack_div {
        display: flex;
        justify-content: flex-end;
        margin-right: 40px;
        margin-top: 80px;
    }
    p {
        font-size: 25px;
        margin : 100px 10px;
        text-align: center;
    }
    .blabla_capture_home {
        width: 60%;
        margin-left: 20%;
    }
    .blabla_capture {
        width: 15%;
        margin-left: 10%;
        margin-top: 25px;
    }
    .book_capture {
        width: 30%;
        margin-left: 35%;
        margin-top: 25px;
    }
 }
   
</style>