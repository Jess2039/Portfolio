<script>
import {link} from 'svelte-spa-router';
</script>

<header class="header">
    <input class="menu-btn" type="checkbox" id="menu-btn" />
    <label class="menu-icon" for="menu-btn"><span class="navicon"></span></label>
        <ul class="menu">
            <li><a href="/" use:link>Accueil</a></li>
            <li><a href="/skills" use:link>Compétences</a></li>
            <li><a href="/portfolio" use:link>Portfolio</a></li>
            <li><a href="/contact" use:link>Contact</a></li>
        </ul>
</header>