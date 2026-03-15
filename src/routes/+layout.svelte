<script>
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
    import Footer from "$lib/components/Footer.svelte";
    import Nav from "$lib/components/Nav.svelte";
    import Header from "$lib/components/Header.svelte";



	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<Header />
<Nav />

{@render children()}

<Footer />

<style>
    @import url('https://fonts.googleapis.com/css2?family=Megrim&display=swap');

    @import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap');

    :global(body) {
         background: url("/images/background.png") no-repeat center center fixed;
         background-size: cover;

         color: white;
         background-color: black;
     }
</style>
