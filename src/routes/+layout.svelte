<script>
    import Footer from "$lib/components/footer/Footer.svelte";
    import Navbar from "$lib/components/navbar/Navbar.svelte";
    import "../app.css";
</script>

<Navbar />
<slot />
<Footer />
