<script>
    import Pamflet from "$lib/assets/pamflet.jpeg";
    import Wahyudi from "$lib/assets/wahyudi.jpeg";
    import Sri from "$lib/assets/suryani.jpeg";
    import Djati from "$lib/assets/djati.jpeg";
    import Tamfis from "$lib/assets/tamanfisika.jpg";
    import Template from "$lib/assets/Template.docx";

    import Speaker from "$lib/ui/Speaker/Speaker.svelte";

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

    const timelines = [
        {
            date: "9 September - 18 Oktober 2024",
            title: "Pendaftaran",
            description:
                "Pendaftaran peserta melalui situs resmi dengan mengisi formulir yang disediakan.",
        },
        {
            date: "5 Oktober 2024",
            title: "Batas Pengiriman Abstrak",
            description:
                "Batas akhir pengiriman abstrak untuk peserta yang telah mendaftar.",
        },
        {
            date: "10 Februari 2025",
            title: "Batas Pengiriman Artikel Penuh",
            description:
                "Batas akhir pengiriman artikel lengkap bagi peserta yang abstraknya disetujui.",
        },
    ];
</script>

<svelte:head>
    <title>Seminar Nasional Fisika | Universitas Hasanuddin</title>
</svelte:head>

<div id="main" class="flex flex-col">
    <!-- Pamflet and Intro Section -->
    <section
        class="flex flex-col lg:flex-row px-4 py-12 gap-x-8 gap-y-4 justify-center items-center"
    >
        <img src={Pamflet} alt="Pamflet SNF 2024" class="w-[500px] h-auto" />
        <div class="text-justify flex flex-col lg:items-start items-center">
            <h1
                class="mb-5 text-2xl lg:text-3xl font-bold text-gray-800 uppercase before:block before:w-24 before:h-3 before:mb-5 sm:before:mx-0 before:bg-gray-800"
            >
                Seminar Nasional Fisika (SNF) 2024
            </h1>
            <p
                class="text-sm lg:text-base lg:leading-loose text-gray-800 italic mb-5"
            >
                Menimbang KEPUTUSAN REKTOR UNIVERSITAS HASANUDDIN NOMOR
                01702/UN4.1/KEP/2024, Departemen Fisika FMIPA Universitas
                Hasanuddin akan menyelenggarakan Seminar Nasional Fisika (SNF)
                Makassar 2024. Seminar nasional fisika menjadi forum untuk
                berbagi pengetahuan terbaru, penelitian, dan temuan dalam bidang
                fisika. Ini memungkinkan para akademisi, peneliti, dan mahasiswa
                untuk memperluas wawasan mereka dan memperbarui pengetahuan
                mereka tentang perkembangan terbaru dalam fisika. Seminar ini
                menyediakan kesempatan bagi para ilmuwan dan peneliti untuk
                bertemu, berdiskusi, dan berkolaborasi dengan rekan sejawat dari
                berbagai institusi dan daerah. Ini dapat mendorong kerjasama
                penelitian dan membangun jaringan profesional yang berguna untuk
                kemajuan ilmu pengetahuan.
            </p>
            <div class="flex gap-5">
                <a
                    href={Pamflet}
                    class="flex bg-blue-800 hover:bg-blue-900 text-sm text-white font-semibold p-2"
                    download="Pamflet"
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
                </a>
                <a
                    href={Template}
                    download="Templat Makalah SNF 2024"
                    class="flex bg-blue-800 hover:bg-blue-900 text-sm text-white font-semibold p-2"
                    >Download Template
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
                </a>
            </div>
        </div>
    </section>

    <!-- Background Section -->
    <section class="flex flex-col justify-center max-w-7xl mx-auto px-4 py-12">
        <h1
            class="mb-5 text-2xl lg:text-3xl font-bold text-gray-800 uppercase before:block before:w-24 before:h-3 before:mb-5 sm:before:mx-0 before:bg-gray-800"
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
    </section>

    <!-- Keynote Speaker Section -->
    <section class="relative flex flex-col justify-center pl-8 lg:pl-24 py-12">
        <div class="bg-gray-950 opacity-90 absolute inset-0 z-10"></div>
        <img
            src={Tamfis}
            alt="Taman Fisika"
            class="absolute inset-0 w-full h-full object-cover z-0"
        />
        <h1
            class="mb-12 text-2xl lg:text-3xl font-extrabold text-gray-200 uppercase z-10 before:block before:w-24 before:h-3 before:mb-5 sm:before:mx-0 before:bg-gray-200"
        >
            Keynote Speaker
        </h1>
        <div class="flex flex-col lg:flex-row gap-x-24 gap-y-10 z-10">
            {#each speakers as speaker}
                <Speaker
                    name={speaker.name}
                    image={speaker.image}
                    title={speaker.title}
                />
            {/each}
        </div>
    </section>

    <!-- Bidang Kajian Section -->
    <section class="flex flex-col px-4 py-12 pl-8 lg:pl-24">
        <h1
            class="mb-10 text-2xl lg:text-3xl font-extrabold text-blue-800 uppercase before:block before:w-24 before:h-3 before:mb-5 sm:before:mx-0 before:bg-blue-800"
        >
            Bidang Kajian Penelitian
        </h1>
        <div class="grid grid-cols-2 lg:grid-cols-3 gap-10">
            {#each scopes as scope}
                <div
                    class="bg-blue-800 text-white lg:w-64 font-semibold text-xs lg:text-base pl-4 p-2 shadow-md cursor-pointer"
                >
                    {scope}
                </div>
            {/each}
        </div>
    </section>

    <!-- Timeline Section -->
    <section class="bg-gray-50">
        <div class="max-w-5xl px-4 py-12 mx-auto">
            <div class="grid gap-4 mx-4 sm:grid-cols-12">
                <div class="col-span-12 sm:col-span-3">
                    <div
                        class="text-center sm:text-left mb-14 before:block before:w-24 before:h-3 before:mb-5 before:mx-auto sm:before:mx-0 before:bg-yellow-500"
                    >
                        <h3 class="text-2xl font-semibold uppercase">
                            Timeline
                        </h3>
                        <span
                            class="text-sm font-bold tracking-wider uppercase text-gray-600"
                            >SNF 2024</span
                        >
                    </div>
                </div>
                <div class="relative col-span-12 px-4 space-y-6 sm:col-span-9">
                    <div
                        class="col-span-12 space-y-12 relative px-4 sm:col-span-8 sm:space-y-8 sm:before:absolute sm:before:top-2 sm:before:bottom-0 sm:before:w-0.5 sm:before:-left-3 before:bg-gray-300"
                    >
                        {#each timelines as timeline}
                            <div
                                class="flex flex-col sm:relative sm:before:absolute sm:before:top-2 sm:before:w-4 sm:before:h-4 sm:before:left-[-35px] sm:before:z-[1] before:bg-yellow-500"
                            >
                                <h3 class="text-xl font-semibold tracking-wide">
                                    {timeline.title}
                                </h3>
                                <time
                                    class="text-xs tracking-wide uppercase text-gray-800"
                                    >{timeline.date}</time
                                >
                                <p class="mt-3">
                                    {timeline.description}
                                </p>
                            </div>
                        {/each}
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="">
        <div class="max-w-5xl px-4 py-12 mx-auto">
            <div class="grid gap-4 mx-4 sm:grid-cols-12">
                <div class="col-span-12 sm:col-span-3">
                    <div
                        class="text-center sm:text-left mb-14 before:block before:w-24 before:h-3 before:mb-5 before:mx-auto sm:before:mx-0 before:bg-blue-800"
                    >
                        <h3 class="text-2xl font-semibold uppercase">
                            Get in touch
                        </h3>
                        <span
                            class="text-sm font-bold tracking-wider uppercase text-gray-600"
                            >Kontak kami</span
                        >
                    </div>
                </div>
                <div class="col-span-12 sm:col-span-9">
                    <div class="grid gap-8 grid-cols-1 sm:grid-cols-2">
                        <div
                            class="bg-white p-6 rounded-lg border border-gray-300"
                        >
                            <h3 class="font-medium mb-2">
                                Ajeng Anggreny Ibrahim, S.Pd., M.Si.
                            </h3>
                            <p class="text-gray-600 mt-2">+62 853-9933-6938</p>
                        </div>
                        <div
                            class="bg-white p-6 rounded-lg border border-gray-300"
                        >
                            <h3 class="font-medium mb-2">
                                Ayu Hardidanti Pratiwi, S.Pd.,M.Si
                            </h3>
                            <p class="text-gray-600 mt-2">+62 821-9447-8721</p>
                        </div>
                        <div
                            class="bg-white p-6 rounded-lg border border-gray-300"
                        >
                            <h3 class="font-medium mb-2">E-Mail</h3>
                            <a
                                href="mailto:hello@example.com"
                                class="text-blue-500 hover:underline"
                                >snfunhas@gmail.com</a
                            >
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-gray-50">
        <div class="max-w-5xl px-4 py-12 mx-auto">
            <div class="grid gap-4 mx-4 sm:grid-cols-12">
                <!-- Title -->
                <div class="col-span-12 sm:col-span-3">
                    <div
                        class="text-center sm:text-left mb-14 before:block before:w-24 before:h-3 before:mb-5 before:mx-auto sm:before:mx-0 before:bg-blue-800"
                    >
                        <h3 class="text-3xl font-semibold uppercase">
                            Location
                        </h3>
                        <span
                            class="text-sm font-bold tracking-wider uppercase text-gray-600"
                            >Lokasi Seminar</span
                        >
                    </div>
                </div>

                <!-- Location Details -->
                <div class="col-span-12 sm:col-span-9">
                    <div class="grid gap-8 grid-cols-1 sm:grid-cols-2">
                        <!-- Offline Venue with Google Maps -->
                        <div
                            class="bg-white p-6 rounded-lg border border-gray-300"
                        >
                            <div class="flex items-center mb-4">
                                <svg
                                    xmlns="http://www.w3.org/2000/svg"
                                    class="h-6 w-6 text-blue-500 mr-2"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke="currentColor"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        stroke-width="2"
                                        d="M12 2C8.134 2 5 5.134 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.866-3.134-7-7-7z"
                                    />
                                    <circle
                                        cx="12"
                                        cy="9"
                                        r="2"
                                        fill="currentColor"
                                    ></circle>
                                </svg>
                                <h3 class="text-xl font-semibold">
                                    Universitas Hasanuddin
                                </h3>
                            </div>
                            <p class="text-gray-600 mb-2">
                                Departemen Fisika, FMIPA
                            </p>
                            <p class="text-gray-600">TBA</p>
                            <p class="text-gray-600 mt-4">
                                Tanggal: 26 Oktober, 2024
                            </p>
                            <p class="text-gray-600">
                                Jam: 08:00 WITA - 17:00 WITA
                            </p>

                            <!-- Google Maps Embed -->
                            <div class="mt-4">
                                <iframe
                                    class="w-full rounded-lg border border-gray-300"
                                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3151.8354345093646!2d144.95592381568324!3d-37.81720997975195!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad642af0f11fd81%3A0xf5770d6a8e5bbfdf!2sUniversity%20of%20Melbourne!5e0!3m2!1sen!2sau!4v1615074192284!5m2!1sen!2sau"
                                    width="100%"
                                    height="200"
                                    style="border:0;"
                                    allowfullscreen=""
                                    loading="lazy"
                                >
                                </iframe>
                            </div>
                        </div>

                        <!-- Online Venue -->
                        <div
                            class="bg-white p-6 rounded-lg border border-gray-300"
                        >
                            <div class="flex items-center mb-4">
                                <svg
                                    xmlns="http://www.w3.org/2000/svg"
                                    class="h-6 w-6 text-blue-500 mr-2"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke="currentColor"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        stroke-width="2"
                                        d="M15 10l4.553-2.276A2 2 0 0118 6.236V4a2 2 0 00-2-2H8a2 2 0 00-2 2v2.236a2 2 0 01-1.553 1.488L4 10m11 0l-1 2m-5-2l1 2m6 8H9m10 0h-4m-8 0H5a2 2 0 01-2-2v-2c0-1.591 1.389-3 3-3h12c1.611 0 3 1.409 3 3v2a2 2 0 01-2 2z"
                                    />
                                </svg>
                                <h3 class="text-xl font-semibold">
                                    Zoom Meeting
                                </h3>
                            </div>
                            <p class="text-gray-600 mb-2">Online via Zoom</p>
                            <a
                                href="https://zoom.us/j/your-meeting-id"
                                class="text-blue-500 hover:underline"
                                >Join Zoom Meeting</a
                            >
                            <p class="text-gray-600 mt-4">
                                Meeting ID: 123-456-789
                            </p>
                            <p class="text-gray-600">Passcode: 987654</p>
                            <p class="text-gray-600 mt-4">
                                Tanggal: 26 Oktober, 2024
                            </p>
                            <p class="text-gray-600">
                                Jam: 08:00 WITA - 17:00 WITA
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</div>
