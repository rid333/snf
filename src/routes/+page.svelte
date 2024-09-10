<script>
    import Pamflet from "$lib/assets/pamflet.jpeg";
</script>

<svelte:head>
    <title>Seminar Nasional Fisika | Universitas Hasanuddin</title>
</svelte:head>

<div id="main">
    <!-- Pamflet and Intro Section -->
    <div
        class="flex flex-col lg:flex-row p-6 gap-x-8 gap-y-4 justify-center items-center"
    >
        <img src={Pamflet} alt="Pamflet SNF 2024" class="w-[550px] h-auto" />
        <div class="text-justify flex flex-col lg:items-start items-center">
            <h1
                class="text-xl lg:text-4xl font-bold mb-5 bg-blue-500 text-white rounded p-3 w-fit"
            >
                Seminar Nasional Fisika (SNF) 2024
            </h1>
            <p class="text-base lg:text-lg leading-relaxed italic mb-5">
                Berdasarkan kenyataan inilah dan menimbang KEPUTUSAN REKTOR
                UNIVERSITAS HASANUDDIN NOMOR 01702/UN4.1/KEP/2024, Departemen
                Fisika FMIPA Universitas Hasanuddin akan menyelenggarakan
                Seminar Nasional Fisika (SNF) Makassar 2024. Seminar nasional
                fisika menjadi forum untuk berbagi pengetahuan terbaru,
                penelitian, dan temuan dalam bidang fisika. Ini memungkinkan
                para akademisi, peneliti, dan mahasiswa untuk memperluas wawasan
                mereka dan memperbarui pengetahuan mereka tentang perkembangan
                terbaru dalam fisika. Seminar ini menyediakan kesempatan bagi
                para ilmuwan dan peneliti untuk bertemu, berdiskusi, dan
                berkolaborasi dengan rekan sejawat dari berbagai institusi dan
                daerah. Ini dapat mendorong kerjasama penelitian dan membangun
                jaringan profesional yang berguna untuk kemajuan ilmu
                pengetahuan.
            </p>
            <button class="flex bg-blue-500 text-white rounded font-medium p-2"
                >Download Pamflet
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    class="w-5 ml-2"
                    viewBox="0 0 16 16"
                >
                    <path
                        d="M.5 9.9a.5.5 0 0 1 .5.5v2.5a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-2.5a.5.5 0 0 1 1 0v2.5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2v-2.5a.5.5 0 0 1 .5-.5"
                    />
                    <path
                        d="M7.646 11.854a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8.5 10.293V1.5a.5.5 0 0 0-1 0v8.793L5.354 8.146a.5.5 0 1 0-.708.708z"
                    />
                </svg>
            </button>
        </div>
    </div>

    <!-- Background Section -->
    <div class="bg-blue-500 text-white p-6">
        <h1 class="text-3xl font-bold mb-5">Latar Belakang</h1>
        <p class="text-lg leading-relaxed italic">
            Seminar Nasional Fisika (SNF) merupakan kegiatan tahunan yang
            diselenggarakan oleh Departemen Fisika FMIPA Universitas Hasanuddin.
            Seminar ini bertujuan untuk memperkenalkan dan memperluas wawasan
            serta pengetahuan dalam bidang fisika. SNF juga menjadi wadah bagi
            para akademisi, peneliti, dan mahasiswa untuk berbagi pengetahuan
            dan pengalaman dalam bidang fisika. Dengan mengikuti SNF, peserta
            diharapkan dapat memperoleh informasi terbaru tentang perkembangan
            ilmu pengetahuan dan teknologi dalam bidang fisika. Selain itu, SNF
            juga menjadi ajang untuk memperluas jaringan kerjasama antar
            peneliti, akademisi, dan mahasiswa dalam bidang fisika.
        </p>
    </div>
</div>
