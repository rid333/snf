<script>
    import Header from "$lib/components/header/Header.svelte";
    import Navbar from "$lib/components/navbar/Navbar.svelte";
    import Footer from "$lib/components/footer/Footer.svelte";
    import "../app.css";
</script>

<Header />
<slot />
<Footer />
