<script>
    import { onMount } from 'svelte';

    onMount(() => {
        console.log('Footer mounted');
    });
</script>

<style>
    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 1rem;
        position: relative;
        bottom: 0;
        width: 100%;
    }

    a {
        color: #61dafb;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }
</style>

<footer>
    <p>&copy; {new Date().getFullYear()} GameStore. Tous droits réservés.</p>
    <p>
        <a href="/mentions-legales">Mentions légales</a> | 
        <a href="/contact">Contact</a>
    </p>
</footer>