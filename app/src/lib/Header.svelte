<script>
import {link} from 'svelte-spa-router';
</script>

<header>
    
    <nav>
        <ul>
            <li><a href="/" use:link>Accueil</a></li>
            <li><a href="/skills" use:link>Compétences</a></li>
            <li><a href="/portfolio" use:link>Portfolio</a></li>
            <li><a href="/contact" use:link>Contact</a></li>
        </ul>
    </nav>
</header>