<script>
    import Logo from "$lib/assets/logounhas.png";
    import Unhas from "$lib/assets/unhas2.jpg";
</script>

<section
    class="min-h-screen text-white flex flex-col justify-between relative bg-black"
>
    <div class="bg-black opacity-75 absolute inset-0 z-10"></div>
    <img
        src={Unhas}
        alt="Universitas Hasanuddin"
        class="absolute inset-0 w-full h-full object-cover z-0"
    />

    <!-- Navbar -->
    <nav
        class="flex text-sm lg:text-base justify-between items-center p-6 z-10"
    >
        <img src={Logo} alt="Fisika" class="w-10 h-10" />
        <ul class="flex space-x-8 font-semibold">
            <li><a href="/" class="hover:text-indigo-400">Home</a></li>
            <li>
                <a href="/panitia" class="hover:text-indigo-400">Panitia</a>
            </li>
            <li><a href="/" class="hover:text-indigo-400">Tentang</a></li>
        </ul>
        <a target="_blank" href="https://forms.gle/m2EqjTxS3FzaLrg36">
            <button
                class="bg-blue-800 hover:bg-blue-900 text-white font-bold py-2 px-4"
            >
                Daftar
            </button>
        </a>
    </nav>

    <!-- Hero Main -->
    <div
        class="flex-grow flex flex-col justify-center items-center px-4 text-center z-10"
    >
        <h1 class="text-3xl md:text-5xl font-bold mb-4">
            SEMINAR NASIONAL FISIKA (SNF) MAKASSAR 2024
        </h1>
        <p class="text-sm lg:text-lg font-semibold text-gray-400 mb-6">
            Enhance The Role Of Applied Physics In Renewable Energy Challenges
            For the Utilities Industry
        </p>
        <div class="flex space-x-4">
            <a
                href="#main"
                class="text-sm lg:text-base flex items-center px-3 py-1.5 lg:px-6 lg:py-3 border-2 border-yellow-600 hover:bg-yellow-600 text-white font-semibold"
                >Baca Selengkapnya
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    class="pl-2 w-6"
                    viewBox="0 0 16 16"
                >
                    <path
                        fill-rule="evenodd"
                        d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708"
                    />
                </svg>
            </a>
        </div>
    </div>
</section>
