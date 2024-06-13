<script>
    import Router from "svelte-spa-router";
    import Header from "./lib/Header.svelte";
    import Home from "./pages/Home.svelte";
    import Skills from "./pages/Skills.svelte";
    import Portfolio from "./pages/Portfolio.svelte";
    import Contact from "./pages/Contact.svelte";
    import Project from "./pages/Project.svelte";
    import Footer from "./lib/Footer.svelte";

    // configuration des routes
    const routes = {
        '/': Home,
        '/skills': Skills,
        '/contact': Contact,
        '/portfolio': Portfolio,
        '/project/:id': Project
    };

</script>




<Header />
<Router {routes} />