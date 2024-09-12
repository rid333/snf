<script>
    import Header from "$lib/components/header/Header.svelte";
    import Footer from "$lib/components/footer/Footer.svelte";
    import "../app.css";
</script>

<Header />
<slot />
<Footer />
