<script>
    import Header from "$lib/components/header/Header.svelte";
    import Footer from "$lib/components/footer/Footer.svelte";
    import "../app.css";
</script>

<div class="fixed bottom-4 right-4 z-50">
    <a
        class="bg-blue-800 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-full shadow-lg"
        href="https://wa.me/6285399336938"
        target="_blank"
    >
        Kontak Kami
    </a>
</div>

<Header />
<slot />
<Footer />
