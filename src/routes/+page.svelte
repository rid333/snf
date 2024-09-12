<script>
    import Pamflet from "$lib/assets/pamflet.jpeg";
    import Wahyudi from "$lib/assets/wahyudi.jpeg";
    import Sri from "$lib/assets/suryani.jpeg";
    import Djati from "$lib/assets/djati.jpeg";
    import Tamfis from "$lib/assets/tamanfisika.jpg";

    const scopes = [
        "Fisika Teori",
        "Fisika Komputasi",
        "Fisika Matematika",
        "Fisika Optik",
        "Fisika Spektroskopi",
        "Fisika Material",
        "Fisika Semikonduktor",
        "Fisika Elektronika",
        "Fisika Instrumentasi",
        "Biomaterial",
        "Nanoteknologi",
        "Fisika Lingkungan",
        "Fisika Oseanografi",
        "Pendidikan Fisika",
        "Fisika Bumi",
        "Sains Atmosfer",
        "Fisika Nuklir",
        "Fisika Medik",
    ];

    const speakers = [
        {
            name: "Prof. Dr. Ing. Wahyudi Basri",
            title: "Badan Riset dan Inovasi Nasional (BRIN)",
            image: Wahyudi,
        },
        {
            name: "Prof. Dr. Sri Suryani, DEA",
            title: "Departemen Fisika Universitas Hasanuddin",
            image: Sri,
        },
        {
            name: "Dr. Djati Handoko, Ph.D.",
            title: "Departemen Fisika Universitas Indonesia",
            image: Djati,
        },
    ];
</script>

<svelte:head>
    <title>Seminar Nasional Fisika | Universitas Hasanuddin</title>
</svelte:head>

<div id="main" class="flex flex-col gap-y-20 py-20">
    <!-- Pamflet and Intro Section -->
    <div
        class="flex flex-col lg:flex-row lg:px-28 gap-x-8 gap-y-4 justify-center items-center"
    >
        <img src={Pamflet} alt="Pamflet SNF 2024" class="w-[500px] h-auto" />
        <div class="text-justify flex flex-col lg:items-start items-center">
            <h1
                class="text-xl lg:text-4xl font-extrabold mb-5 text-gray-800 rounded w-fit uppercase"
            >
                Seminar Nasional Fisika (SNF) 2024
            </h1>
            <p
                class="text-sm lg:text-base lg:leading-loose text-gray-800 italic mb-5"
            >
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
            <button
                class="flex bg-blue-800 hover:bg-blue-900 lg:text-sm text-white rounded font-medium p-2"
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
    <div class="flex flex-col justify-center items-center lg:px-20">
        <h1
            class="mb-5 text-2xl lg:text-4xl font-extrabold text-gray-800 uppercase"
        >
            Latar Belakang
        </h1>
        <div
            class="flex flex-col gap-y-3 text-gray-800 text-base lg:text-lg text-justify"
        >
            <p>
                Para ahli diharapkan untuk melakukan riset dalam berbagai
                disiplin ilmu sehingga bisa menjadikan ilmu sains khususnya ilmu
                fisika menjadi penguat utama dalam riset. Ketika dunia bergulat
                dengan kebutuhan mendesak untuk melakukan transisi menuju sumber
                energi berkelanjutan, peran fisika dalam mengatasi tantangan
                yang dihadapi oleh industri utilitas menjadi semakin penting.
                Untuk menavigasi lanskap yang kompleks ini, perusahaan utilitas
                harus beradaptasi dan mengadopsi solusi inovatif yang
                memanfaatkan prinsip-prinsip dasar fisika. Salah satu bidang
                utama di mana fisika memainkan peran penting adalah dalam
                pengembangan teknologi elektronika daya.
            </p>
            <p>
                Fisika sering kali terlibat dalam penelitian dan pengembangan
                solusi untuk tantangan global seperti energi, lingkungan, dan
                kesehatan. Seminar ini bisa menjadi wadah untuk mendiskusikan
                bagaimana fisika dapat berkontribusi pada solusi isu-isu besar
                tersebut. Kompleksitas ilmu Fisika sebagai core of science
                dengan berbagai fenomenanya sangat dapat diimplementasikan di
                berbagai topik riset. Untuk itu para Fisikawan harus mampu
                berfikir secara inovatif dan strategis dalam menyeimbangkan
                antara teori dan praktek nyata sehingga hasilnya dapat
                dimanfaatkan untuk kemaslahatan umat manusia. Melalui prinsip
                Tri Dharma Perguruan Tinggi, meliputi pendidikan, penelitian,
                dan pengabdian pada masyarakat, para akademisi dan peneliti
                diharapkan tetap berkontribsi secara nyata untuk mempublikasikan
                hasil penelitiannya agar kepakarannya sebagai peneliti
                meningkat. Kualitas penelitian dapat dilihat dari banyaknya
                akademisi dan peneliti yang mempublikasikan karyanya di jurnal
                internasional terindeks sehingga dapat menjadi sumber bahan ajar
                dalam pengembangan kurikulum (K23) di Unhas.
            </p>
            <p>
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
        </div>
    </div>

    <!-- Keynote Speaker Section -->
    <div
        class="relative flex flex-col justify-center items-center p-3 lg:px-20 lg:py-20"
    >
        <div class="bg-black opacity-50 absolute inset-0 z-10"></div>
        <img
            src={Tamfis}
            alt="Taman Fisika"
            class="absolute inset-0 w-full h-full object-cover z-0"
        />
        <h1
            class="mb-5 text-2xl lg:text-4xl font-extrabold text-gray-100 mb-20 uppercase z-10"
        >
            Keynote Speaker
        </h1>
        <div class="flex flex-col lg:flex-row gap-x-10 z-10">
            {#each speakers as speaker}
                <div class="flex flex-col gap-y-4">
                    <img
                        src={speaker.image}
                        alt={speaker.name}
                        class="w-72 h-72 object-cover mb-3 lg:mb-0"
                    />
                    <div>
                        <p
                            class="font-extrabold text-2xl text-yellow-500 uppercase"
                        >
                            {speaker.name}
                        </p>
                        <p class="text-white font-medium text-xl">
                            {speaker.title}
                        </p>
                    </div>
                </div>
            {/each}
        </div>
    </div>

    <!-- Bidang Kajian Section -->
    <div class="flex flex-col justify-center items-center p-3 lg:p-6">
        <h1
            class="mb-5 text-2xl lg:text-4xl font-extrabold text-blue-800 uppercase"
        >
            Bidang Kajian Penelitian
        </h1>
        <div class="grid grid-cols-3 justify-items-center gap-y-7">
            {#each scopes as scope}
                <div
                    class="bg-blue-800 text-white w-64 font-semibold text-base p-2 shadow-md rounded text-center cursor-pointer"
                >
                    {scope}
                </div>
            {/each}
        </div>
    </div>
</div>
