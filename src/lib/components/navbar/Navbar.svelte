<script>
    import Logo from "$lib/assets/logounhas.png";
</script>

<nav class="fixed top-0 w-full flex justify-between items-center p-6 z-10">
    <img src={Logo} alt="Fisika" class="w-10 h-10" />
    <ul class="flex space-x-8 font-semibold">
        <li><a href="/" class="hover:text-indigo-400">Home</a></li>
        <li>
            <a href="/panitia" class="hover:text-indigo-400">Panitia</a>
        </li>
        <li><a href="/" class="hover:text-indigo-400">Tentang</a></li>
    </ul>
    <a target="_blank" href="https://forms.gle/w7Z23vkLp3rkZ3cq8">
        <button
            class="bg-blue-800 hover:bg-blue-900 text-white font-bold py-2 px-4"
        >
            Submit
        </button>
    </a>
</nav>
