<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carian Direktori Pensyarah</title>
    <!-- Menggunakan Tailwind CSS untuk rekaan moden yang pantas -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Animasi untuk kotak carian ala Google */
        .search-container {
            transition: all 0.5s ease-in-out;
        }
        .search-center {
            margin-top: 20vh;
        }
        .search-top {
            margin-top: 2rem;
            padding-bottom: 1rem;
            border-bottom: 1px solid #e5e7eb;
        }
        .google-logo {
            font-family: 'Product Sans', Arial, sans-serif;
            font-weight: 700;
            letter-spacing: -1px;
        }
        .google-blue { color: #4285F4; }
        .google-red { color: #EA4335; }
        .google-yellow { color: #FBBC05; }
        .google-green { color: #34A853; }
        
        /* Hilangkan scrollbar melintang */
        body { overflow-x: hidden; }
    </style>
</head>
<body class="bg-white text-gray-800 min-h-screen flex flex-col font-sans antialiased">

    <!-- Bekas Utama (Main Container) -->
    <div id="main-container" class="max-w-4xl mx-auto w-full px-4 search-container search-center">
        
        <!-- Logo -->
        <div id="logo-container" class="text-center mb-8">
            <h1 class="text-5xl md:text-6xl google-logo select-none">
                <span class="google-blue">D</span><span class="google-red">i</span><span class="google-yellow">r</span><span class="google-blue">e</span><span class="google-green">c</span><span class="google-red">t</span><span class="google-yellow">o</span><span class="google-blue">r</span><span class="google-green">y</span>
            </h1>
            <p class="text-gray-500 mt-2 text-sm md:text-base">Carian Maklumat Pensyarah UiTM Perlis</p>
        </div>

        <!-- Kotak Carian -->
        <div class="relative w-full max-w-2xl mx-auto shadow-sm hover:shadow-md transition-shadow rounded-full border border-gray-200 focus-within:shadow-md">
            <div class="absolute inset-y-0 left-0 flex items-center pl-4 pointer-events-none">
                <svg class="w-5 h-5 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                </svg>
            </div>
            <input type="text" id="searchInput" class="block w-full p-4 pl-12 text-sm text-gray-900 bg-transparent rounded-full border-none focus:ring-0 focus:outline-none" placeholder="Cari nama, jawatan, fakulti, atau emel..." autocomplete="off">
            <div id="clearBtn" class="absolute inset-y-0 right-0 flex items-center pr-4 cursor-pointer hidden text-gray-400 hover:text-gray-600">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                </svg>
            </div>
        </div>
    </div>

    <!-- Kawasan Keputusan Carian -->
    <div id="results-container" class="max-w-4xl mx-auto w-full px-4 mt-6 hidden pb-12">
        <p id="results-count" class="text-sm text-gray-500 mb-4"></p>
        <div id="results-list" class="flex flex-col gap-6">
            <!-- Kad keputusan akan dijana di sini oleh JavaScript -->
        </div>
    </div>

    <!-- JAVASCRIPT & DATA JSON -->
    <script>
        /**
         * DATA JSON (Diambil daripada sebahagian fail Excel anda)
         * Anda boleh menggantikan array ini dengan keseluruhan data dari column 'code' Excel anda.
         */
        const pensyarahData = [
            { nama: "RIZAUDDIN BIN SAIAN (PM DR)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B2-64", blok: "HEA", extension: "04-9882770", email: "rizauddin@uitm.edu.my", gambar: "https://drive.google.com/file/d/12HV-YEVr6fmIbvvT1YGcVQmKLXdlVKVP/view?usp=drive_link" },
{ nama: "SHUKOR SANIM BIN MOHD FAUZI (PM Ts DR)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F105", blok: "STAR", extension: "04-9882270", email: "shukorsanim@uitm.edu.my", gambar: "" },
{ nama: "ABDUL HAPES BIN MOHAMMED", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-77", blok: "HEA", extension: "04-9882776", email: "hapes@uitm.edu.my", gambar: "" },
{ nama: "AHMAD YUSRI BIN DAK (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F137", blok: "STAR", extension: "04-9882265", email: "ahmadyusri@uitm.edu.my", gambar: "" },
{ nama: "ALIF FAISAL BIN IBRAHIM", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B2-08", blok: "HEA", extension: "04-9882803", email: "aliffaisal@uitm.edu.my", gambar: "" },
{ nama: "ANAS BIN FATHUL ARIFFIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-59", blok: "HEA", extension: "04-9882742", email: "anasfathul@uitm.edu.my", gambar: "" },
{ nama: "AZLAN ABDUL AZIZ", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B2-28", blok: "HEA", extension: "04-9882891", email: "azlan172@uitm.edu.my", gambar: "" },
{ nama: "AZMI ABU SEMAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F134", blok: "STAR", extension: "04-9882260", email: "azmi384@uitm.edu.my", gambar: "" },
{ nama: "AZNOORA BINTI OSMAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-62", blok: "HEA", extension: "04-9882321", email: "aznoora@uitm.edu.my", gambar: "" },
{ nama: "BALKIAH BINTI MOKTAR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-05", blok: "HEA", extension: "04-9882753", email: "balkiah@uitm.edu.my", gambar: "" },
{ nama: "DIANA SIRMAYUNIE BINTI MOHD NASIR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-19", blok: "HEA", extension: "04-9882743", email: "dianasirmayunie@uitm.edu.my", gambar: "" },
{ nama: "HANISAH BINTI AHMAD", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-68", blok: "HEA", extension: "04-9882830", email: "hanisahahmad@uitm.edu.my", gambar: "" },
{ nama: "HAWA BINTI MOHD EKHSAN (Ts.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-21", blok: "HEA", extension: "04-9882768", email: "hawame@uitm.edu.my", gambar: "" },
{ nama: "HUDA ZUHRAH BINTI AB HALIM (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "C207-P1-A", blok: "C", extension: "04-9882154", email: "hudazuhrah@uitm.edu.my", gambar: "" },
{ nama: "IMAN HAZWAM BIN ABD HALIM", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-78", blok: "HEA", extension: "04-9882810", email: "hazwam688@uitm.edu.my", gambar: "" },
{ nama: "JASMANI BINTI BIDIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-70", blok: "HEA", extension: "04-9882740", email: "jasmani@uitm.edu.my", gambar: "" },
{ nama: "JIWA NORIS BIN HAMID", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-45", blok: "HEA", extension: "04-9882723", email: "jiwa_noris@uitm.edu.my", gambar: "" },
{ nama: "KHAIRU AZLAN BIN ABD AZIZ", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-21", blok: "HEA", extension: "04-9882693", email: "khairu493@uitm.edu.my", gambar: "" },
{ nama: "KHAIRUL ANWAR B SEDEK (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F136.", blok: "STAR", extension: "04-9882921", email: "khairulanwarsedek@uitm.edu.my", gambar: "" },
{ nama: "KU AZLINA BT KU AKIL", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-08", blok: "HEA", extension: "04-9882716", email: "kuazlina@uitm.edu.my", gambar: "" },
{ nama: "MAHFUDZAH BINTI OTHMAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F138", blok: "STAR", extension: "04-9882262", email: "fudzah@uitm.edu.my", gambar: "" },
{ nama: "MOHAMAD NAJIB BIN MOHAMAD FADZIL", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-67", blok: "HEA", extension: "04-9882823", email: "mohamadnajib@uitm.edu.my", gambar: "" },
{ nama: "MOHAMMAD HAFIZ BIN ISMAIL", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-24", blok: "HEA", extension: "04-9882896", email: "mohammadhafiz@uitm.edu.my", gambar: "" },
{ nama: "MOHD FARIS BIN MOHD FUZI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B2-03", blok: "HEA", extension: "04-9882879", email: "farisfuzi@uitm.edu.my", gambar: "" },
{ nama: "MOHD FAZRIL IZHAR BIN MOHD IDRIS", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-22", blok: "HEA", extension: "04-9882616", email: "fazrilizhar@uitm.edu.my", gambar: "" },
{ nama: "MOHD NIZAM BIN OSMAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-58", blok: "HEA", extension: "04-9882613", email: "mohdnizam@uitm.edu.my", gambar: "" },
{ nama: "MUHAMAD ARIF BIN HASHIM", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-74", blok: "HEA", extension: "04-9882892", email: "muhamadarif487@uitm.edu.my", gambar: "" },
{ nama: "MUHAMAD HASBULLAH BIN MOHD RAZALI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B2-67", blok: "HEA", extension: "04-9882360", email: "hasbullah782@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD NABIL FIKRI BIN JAMALUDDIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F204C", blok: "STAR", extension: "04-9882247", email: "nabilfikri@uitm.edu.my", gambar: "" },
{ nama: "NADIA BT ABDUL WAHAB (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F009", blok: "STAR", extension: "04-9882283", email: "nadiawahab@uitm.edu.my", gambar: "" },
{ nama: "NAEMAH BT ABDUL WAHAB", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-64", blok: "E", extension: "04-9882762", email: "naema586@uitm.edu.my", gambar: "" },
{ nama: "NOORFAIZALFARID BIN MOHD NOOR (Ts.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-26", blok: "HEA", extension: "04-9882708", email: "nfaizalf@uitm.edu.my", gambar: "" },
{ nama: "NOR ARZAMI BIN OTHMAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-55", blok: "HEA", extension: "04-9882783", email: "arzami@uitm.edu.my", gambar: "" },
{ nama: "NOR AZRIANI BINTI MOHAMAD NOR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-57", blok: "HEA", extension: "04-9882857", email: "norazriani@uitm.edu.my", gambar: "" },
{ nama: "NOR HAYATI BINTI SHAFII", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-20", blok: "HEA", extension: "04-9882777", email: "norhayatishafii@uitm.edu.my", gambar: "" },
{ nama: "NORA YANTI BINTI CHE JAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-39", blok: "HEA", extension: "04-9882357", email: "noray084@uitm.edu.my", gambar: "" },
{ nama: "NORFIZA BINTI IBRAHIM (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F008", blok: "STAR", extension: "04-9882219", email: "norfiza@uitm.edu.my", gambar: "" },
{ nama: "NURIZATUL SYAFINAS AHMAD BAKHTIAR (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "i-10", blok: "C", extension: "04-9882153", email: "nurizatul@uitm.edu.my", gambar: "" },
{ nama: "NORPAH BINTI MAHAT", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-63", blok: "HEA", extension: "04-9882806", email: "norpah020@uitm.edu.my", gambar: "" },
{ nama: "NORZIANA BINTI YAHYA (Ts. DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B2-62", blok: "HEA", extension: "04-9882765", email: "norzianayahya@uitm.edu.my", gambar: "" },
{ nama: "NUR FATIHAH BINTI FAUZI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-79", blok: "HEA", extension: "04-9882829", email: "fatihah@uitm.edu.my", gambar: "" },
{ nama: "NUR FAZLIANA RAHIM (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-72", blok: "E", extension: "04-9882174", email: "fazlianarahim@uitm.edu.my", gambar: "" },
{ nama: "NUR IZZATI BINTI KHAIRUDIN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "i-09", blok: "C", extension: "04-9882155", email: "zatkhairudin@uitm.edu.my", gambar: "" },
{ nama: "NUR KHAIRANI BINTI KAMARUDIN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-17", blok: "HEA", extension: "04-9882839", email: "nurkhairani@uitm.edu.my", gambar: "" },
{ nama: "NURIDAWATI BINTI BAHAROM", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "J-05", blok: "J", extension: "04-9882764", email: "nuridawati@uitm.edu.my", gambar: "" },
{ nama: "NURTIHAH MOHAMED NOOR (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B2-37", blok: "E", extension: "04-9882100", email: "nurtihah@uitm.edu.my", gambar: "" },
{ nama: "NURUL HIDAYAH BINTI AB RAJI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "J-04", blok: "J", extension: "04-9882688", email: "hidayah417@uitm.edu.my", gambar: "" },
{ nama: "NURZAID B MUHD ZAIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-65", blok: "HEA", extension: "04-9882856", email: "nurzaid@uitm.edu.my", gambar: "" },
{ nama: "RAFIZA BT RUSLAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-66", blok: "HEA", extension: "04-9882681", email: "rafiza.ruslan@uitm.edu.my", gambar: "" },
{ nama: "RAIHANA BINTI ZAINORDIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "H-09", blok: "HEA", extension: "04-9882758", email: "raihana420@uitm.edu.my", gambar: "" },
{ nama: "RASHIDAH BINTI RAMLE", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-13", blok: "HEA", extension: "04-9882837", email: "rashidahramle@uitm.edu.my", gambar: "" },
{ nama: "ROMIZA BINTI MD NOR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "F135", blok: "STAR", extension: "04-9882261", email: "romiza@uitm.edu.my", gambar: "" },
{ nama: "ROS SYAMSUL BIN HAMID", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "C207-P3-A", blok: "C", extension: "04-9882156", email: "rossyamsul@uitm.edu.my", gambar: "" },
{ nama: "SHARIFAH FHAHRIYAH BT SYED ABAS", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-60", blok: "HEA", extension: "04-9882808", email: "sfhahriyah@uitm.edu.my", gambar: "" },
{ nama: "SITI FATIMAH BINTI ABDUL RAHMAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "H-07", blok: "H", extension: "04-9882799", email: "sitifatimah471@uitm.edu.my", gambar: "" },
{ nama: "SITI HAFAWATI BINTI JAMALUDDIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B0-61", blok: "HEA", extension: "04-9882326", email: "hafawati832@uitm.edu.my", gambar: "" },
{ nama: "SITI SARAH BINTI RASELI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "J-09", blok: "J", extension: "04-9882714", email: "sitisarahraseli@uitm.edu.my", gambar: "" },
{ nama: "SITI ZULAIHA BINTI AHMAD (Ts. DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-25", blok: "HEA", extension: "04-9882838", email: "sitizulaiha@uitm.edu.my", gambar: "" },
{ nama: "SUZANAWATI BINTI ABU HASAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-57", blok: "HEA", extension: "04-9882702", email: "suzan540@uitm.edu.my", gambar: "" },
{ nama: "TEOH YEONG KIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-18", blok: "HEA", extension: "04-9882521", email: "ykteoh@uitm.edu.my", gambar: "" },
{ nama: "UMI HANIM MAZLAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "J-08", blok: "J", extension: "04-9882478", email: "umihanim462@uitm.edu.my", gambar: "" },
{ nama: "WAN NURSHAZELIN BINTI WAN SHAHIDAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-71", blok: "HEA", extension: "04-9882820", email: "shazelin804@uitm.edu.my", gambar: "" },
{ nama: "ZULFIKRI BIN PAIDI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-63", blok: "HEA", extension: "04-9882843", email: "fikri@uitm.edu.my", gambar: "" },
{ nama: "NURUL ATIKAH ROMLI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "E104-P6", blok: "E", extension: "04-9882178", email: "atiqahromli@uitm.edu.my", gambar: "" },
{ nama: "IZLEEN BINTI IBRAHIM", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-61", blok: "HEA", extension: "04-9882823", email: "izleen373@uitm.edu.my", gambar: "" },
{ nama: "MOHD HALIMI BIN AB HAMID", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "J-02", blok: "E", extension: "04-9882103", email: "halimi@uitm.edu.my", gambar: "" },
{ nama: "NURUL HIDAYAH BINTI AHMAD ZUKRI", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-76", blok: "HEA", extension: "04-9882851", email: "hidayah1278@uitm.edu.my", gambar: "" },
{ nama: "RAY ADDERLEY JM. GINING", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "C201-P6", blok: "C", extension: "04-9882183", email: "ray_adderley@uitm.edu.my", gambar: "" },
{ nama: "SITI NOR NADRAH BINTI MUHAMAD", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-59", blok: "HEA", extension: "04-9882516", email: "nadrahmuhamad@uitm.edu.my", gambar: "" },
{ nama: "SITI SARAH BINTI MD ILYAS", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Komputer dan Matematik (FSKM)", bilik: "B1-60", blok: "C", extension: "04-9882107", email: "sarahilyas@uitm.edu.my", gambar: "" },
{ nama: "MOHD AZWAN BIN ABBAS (Sr DR)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Alam Bina (FAB)", bilik: "F106", blok: "STAR", extension: "04-9882530", email: "mohdazwan@uitm.edu.my", gambar: "" },
{ nama: "NURUL AIN BINTI MOHD ZAKI (DR)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-17", blok: "A", extension: "04-9882855", email: "nurulain86@uitm.edu.my", gambar: "" },
{ nama: "ASHRAF BIN ABDULLAH (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "F215", blok: "STAR", extension: "04-9882294", email: "ashraf@uitm.edu.my", gambar: "" },
{ nama: "FARADINA BINTI MARZUKHI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B1-19", blok: "HEA", extension: "04-9882754", email: "faradina454@uitm.edu.my", gambar: "" },
{ nama: "FAZLY AMRI BIN MOHD (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "F217", blok: "STAR", extension: "04-9882295", email: "fazly510@uitm.edu.my", gambar: "" },
{ nama: "ISMAIL BIN MA'AROF (Sr DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "A103", blok: "A", extension: "04-9882679", email: "ismailmaarof@uitm.edu.my", gambar: "" },
{ nama: "KHAIRIL AFENDY BIN HASHIM (Sr Dr)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-16", blok: "HEA", extension: "04-9882883", email: "khairilafendy@uitm.edu.my", gambar: "" },
{ nama: "KHAIRULAZHAR BIN ZAINUDDIN (Sr) (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B307", blok: "B", extension: "04-9882198", email: "khairul760@uitm.edu.my", gambar: "" },
{ nama: "MASAYU BINTI NORMAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B1-24", blok: "HEA", extension: "04-9882689", email: "masayu678@uitm.edu.my", gambar: "" },
{ nama: "MIMI DIANA BINTI GHAZALI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B0-14", blok: "HEA", extension: "04-9882715", email: "mimidiana@uitm.edu.my", gambar: "" },
{ nama: "MOHAMAD ASRUL BIN MUSTAFAR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-26", blok: "HEA", extension: "04-9882852", email: "mohamadasrul@uitm.edu.my", gambar: "" },
{ nama: "MOHAMAD AZRIL BIN CHE AZIZ", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-24", blok: "HEA", extension: "04-9882610", email: "azril060@uitm.edu.my", gambar: "" },
{ nama: "MOHD ADHAR BIN ABD SAMAD", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-39", blok: "HEA", extension: "04-9882899", email: "adhar260@uitm.edu.my", gambar: "" },
{ nama: "MOHD ADLY BIN ROSLY (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-13", blok: "HEA", extension: "04-9882842", email: "mohdadly@uitm.edu.my", gambar: "" },
{ nama: "MOHD KHAIRY BIN KAMARUDIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "A110", blok: "A", extension: "04-9882841", email: "mohdkhairy@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD FAIZ BIN PA'SUYA (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "A211", blok: "A", extension: "04-9882831", email: "faiz524@uitm.edu.my", gambar: "" },
{ nama: "NORSHAHRIZAN BIN MOHD HASHIM (Sr DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-60", blok: "HEA", extension: "04-9882897", email: "norshahrizan@uitm.edu.my", gambar: "" },
{ nama: "ROHAYU BINTI HARON NARASHID (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B1-55", blok: "HEA", extension: "04-9882320", email: "rohayuharon@uitm.edu.my", gambar: "" },
{ nama: "SAMSURI BIN MOHD SALLEH", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-01", blok: "HEA", extension: "04-9882327", email: "samsuri@uitm.edu.my", gambar: "" },
{ nama: "SHARIFAH NORASHIKIN BINTI BOHARI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "A210", blok: "A", extension: "04-9882769", email: "ashikin10@uitm.edu.my", gambar: "" },
{ nama: "SITI AMINAH BINTI ANSHAH", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B1-28", blok: "HEA", extension: "04-9882733", email: "sitiaminah455@uitm.edu.my", gambar: "" },
{ nama: "SITI MARYAM BINTI ABDUL WAHAB", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B1-54", blok: "HEA", extension: "04-9882507", email: "sitimaryam@uitm.edu.my", gambar: "" },
{ nama: "SITI NOR MAIZAH BINTI SAAD (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "A111", blok: "A", extension: "04-9882872", email: "normaizah@uitm.edu.my", gambar: "" },
{ nama: "SUHAILA BINTI HASHIM", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B0-18", blok: "HEA", extension: "04-9882798", email: "suhailah@uitm.edu.my", gambar: "" },
{ nama: "TENGKU AFRIZAL BIN TENGKU ALI (Sr)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B211", blok: "B", extension: "04-9882687", email: "tengkuafrizal@uitm.edu.my", gambar: "" },
{ nama: "ZAKI BIN AHMAD DAHLAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-21", blok: "HEA", extension: "04-9882696", email: "zaki@uitm.edu.my", gambar: "" },
{ nama: "AKRAM ZULKIFLI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Alam Bina (FAB)", bilik: "A117P", blok: "A", extension: "04-9882812", email: "akramzulkifli@uitm.edu.my", gambar: "" },
{ nama: "ASHNITA BINTI RAHIM", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B1-22", blok: "HEA", extension: "04-9882805", email: "ashnita@uitm.edu.my", gambar: "" },
{ nama: "IKHWAN BIN MOHAMED", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-38", blok: "HEA", extension: "04-9882731", email: "ikhwan238@uitm.edu.my", gambar: "" },
{ nama: "MOHD ZAINEE BIN ZAINAL", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "A203P", blok: "", extension: "04-9882858", email: "zainee952@uitm.edu.my", gambar: "" },
{ nama: "NOORAZWANI BINTI MOHD RAZI", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "C201-P2-B", blok: "C", extension: "04-9882151", email: "azwanirazi@uitm.edu.my", gambar: "" },
{ nama: "NOORFATEKAH BINTI TALIB", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-58", blok: "HEA", extension: "04-9882770", email: "noorf492@uitm.edu.my", gambar: "" },
{ nama: "NOORZALIANEE BINTI GHAZALI", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B0-54", blok: "HEA", extension: "04-9882690", email: "zalianee794@uitm.edu.my", gambar: "" },
{ nama: "NURHAFIZA BT MD SAAD", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B2-54", blok: "HEA", extension: "04-9882756", email: "nurhafizasaad@uitm.edu.my", gambar: "" },
{ nama: "NURSYAHANI BINTI NASRON", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B203P", blok: "B", extension: "04-9882566", email: "nursy6864@uitm.edu.my", gambar: "" },
{ nama: "ZURAIHAN BINTI MOHAMAD", jawatan: "PENSYARAH", fakulti: "Fakulti Alam Bina (FAB)", bilik: "B306P", blok: "B", extension: "04-9882187", email: "zuraihan486@uitm.edu.my", gambar: "" },
{ nama: "NORAINI ISMAIL", jawatan: "PENSYARAH KANAN", fakulti: "Jabatan Undang-Undang (LAW)", bilik: "B0-36", blok: "HEA", extension: "04-9882871", email: "noraini2843@uitm.edu.my", gambar: "" },
{ nama: "SITI ASISHAH BINTI HASSAN (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Jabatan Undang-Undang (LAW)", bilik: "B0-23", blok: "HEA", extension: "04-9882707", email: "asishah879@uitm.edu.my", gambar: "" },
{ nama: "ZETI ZURYANI BINTI MOHD ZAKUAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Jabatan Undang-Undang (LAW)", bilik: "B2-61", blok: "HEA", extension: "04-9882824", email: "zeti@uitm.edu.my", gambar: "" },
{ nama: "AHMAD FIKRI BIN MOHD KASSIM (DR.)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "F220", blok: "HEA", extension: "04-9882618", email: "ahmadfikri@uitm.edu.my", gambar: "" },
{ nama: "AHMAD DZULKARNAIN BIN ISMAIL (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-47", blok: "HEA", extension: "04-9882705", email: "ahmad409@uitm.edu.my", gambar: "" },
{ nama: "AZZURA BINTI KAMARUDIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B1-43", blok: "HEA", extension: "04-9882895", email: "azzura@uitm.edu.my", gambar: "" },
{ nama: "ELLAIL AIN BINTI MOHD AZNAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-52", blok: "HEA", extension: "04-9882710", email: "ellailain@uitm.edu.my", gambar: "" },
{ nama: "HARRIS KAMAL BIN KAMARUDDIN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-56", blok: "HEA", extension: "04-9882751", email: "harris540@uitm.edu.my", gambar: "" },
{ nama: "MOHD FARIDZ BIN AHMAD (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-49", blok: "HEA", extension: "04-9882746", email: "faridzahmad@uitm.edu.my", gambar: "" },
{ nama: "MOHD SYAFIQ BIN MISWAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-50", blok: "HEA", extension: "04-9882763", email: "syafiqmiswan@uitm.edu.my", gambar: "" },
{ nama: "NURUL FARHA BINTI ZAINUDDIN (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-48", blok: "HEA", extension: "04-9882316", email: "nurulfarha@uitm.edu.my", gambar: "" },
{ nama: "SYED SHAHBUDIN BIN SYED OMAR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-46", blok: "HEA", extension: "04-9882729", email: "syedshahbudin@uitm.edu.my", gambar: "" },
{ nama: "MOHD SHAH BIN KAMARUDIN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-27", blok: "HEA", extension: "04-9882787", email: "mohdshahkamarudin@uitm.edu.my", gambar: "" },
{ nama: "AL HAFIZ BIN ABU BAKAR", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-57", blok: "HEA", extension: "04-9882780", email: "alhafizab@uitm.edu.my", gambar: "" },
{ nama: "HARITH RUSYDIN ABD RAHMAN", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B1-52", blok: "HEA", extension: "04-9882170", email: "harithrusydin@uitm.edu.my", gambar: "" },
{ nama: "JAMILAH BINTI AHMAD RADZI", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-36", blok: "HEA", extension: "04-9882815", email: "jamilaharadzi@uitm.edu.my", gambar: "" },
{ nama: "MASSHERA BINTI JAMALUDIN", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-65", blok: "HEA", extension: "04-9882698", email: "masshera507@uitm.edu.my", gambar: "" },
{ nama: "MOHD FAIZ PUTRA BIN ABD RAZAK", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B0-46", blok: "HEA", extension: "04-9882793", email: "mohdfa90@uitm.edu.my", gambar: "" },
{ nama: "MOHD KHAIRULANWAR BIN MD YUSOF", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-45", blok: "HEA", extension: "04-9882759", email: "m_khairulanwar@uitm.edu.my", gambar: "" },
{ nama: "MOHD KHALIL AZHAM ABU BAKAR", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "E201-P1-B", blok: "F2", extension: "04-9882170", email: "khalilazham@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD FARID HILMI AIDIT", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-51", blok: "HEA", extension: "04-9882822", email: "faridhilmi@uitm.edu.my", gambar: "" },
{ nama: "NOR NANDINIE BINTI MOHD NIZAM EDROS", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B1-38", blok: "E", extension: "04-9882774", email: "nornandinie@uitm.edu.my", gambar: "" },
{ nama: "NORFAEZAH BINTI MOHD ROSLI", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-40", blok: "HEA", extension: "04-9882324", email: "faezah_rosli@uitm.edu.my", gambar: "" },
{ nama: "NUR AMIRAH BINTI ZAKER", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "E201-P3-A", blok: "F2", extension: "04-9882172", email: "amirahzaker@uitm.edu.my", gambar: "" },
{ nama: "NURAIMI BINTI OTHMAN", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-41", blok: "HEA", extension: "04-9882719", email: "nuraimi128@uitm.edu.my", gambar: "" },
{ nama: "NURUL AFIQAH BINTI BAKAR", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-20", blok: "HEA", extension: "04-9882319", email: "nurulafiqah_bakar@uitm.edu.my", gambar: "" },
{ nama: "SITI AMALINA MOHD YAZID", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B0-11", blok: "HEA", extension: "04-9882744", email: "amalina2311@uitm.edu.my", gambar: "" },
{ nama: "SITI HANNARIAH BINTI MANSOR", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-44", blok: "HEA", extension: "04-9882612", email: "sitihannariah@uitm.edu.my", gambar: "" },
{ nama: "SITI JAMEELAH BINTI MD JAPILUS", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-35", blok: "HEA", extension: "04-9882890", email: "sitijameelah@uitm.edu.my", gambar: "" },
{ nama: "WAN NORSAIDATINA HASMA WAN NAWANG", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "E201-P2-A", blok: "F2", extension: "04-9882171", email: "norsaidatina@uitm.edu.my", gambar: "" },
{ nama: "ZULKIFLI BIN ISMAIL", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Sukan & Rekreasi (FSR)", bilik: "B2-66", blok: "HEA", extension: "04-9882355", email: "zulkifliismail@uitm.edu.my", gambar: "" },
{ nama: "KHUDZIR BIN HJ ISMAIL (Prof. Dr. Hj)(106645)", jawatan: "PROFESOR KEHORMAT", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F121", blok: "STAR", extension: "04-9882277", email: "khudzir@uitm.edu.my", gambar: "" },
{ nama: "MOHD AZLAN BIN MOHD ISHAK (Ts DR)", jawatan: "PROFESOR", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F120", blok: "STAR", extension: "04-9882273", email: "azlanishak@uitm.edu.my", gambar: "" },
{ nama: "NAFISAH BINTI MOHD ISA @ OSMAN (DR)", jawatan: "PROFESOR", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F119", blok: "STAR", extension: "04-9882272", email: "fisha@uitm.edu.my", gambar: "" },
{ nama: "RAZIF BIN MUHAMMED NORDIN (DR)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F014", blok: "STAR", extension: "04-9882253", email: "razifmn@uitm.edu.my", gambar: "" },
{ nama: "WAN IZHAN NAWAWI BIN WAN ISMAIL (PROF MADYA DR)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "G202", blok: "G", extension: "2570/2305", email: "wi_nawawi@uitm.edu.my", gambar: "" },
{ nama: "ABU HASSAN NORDIN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "C207-P2-A", blok: "C", extension: "04-9882176", email: "abuhassannordin@uitm.edu.my", gambar: "" },
{ nama: "AHMAD SUHAIL BIN KHAZALI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F209-A", blok: "C", extension: "04-9882249", email: "ahmadsuhail@uitm.edu.my", gambar: "" },
{ nama: "ANG LEE SIN (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "M.Fizik", blok: "", extension: "-", email: "anglee631@uitm.edu.my", gambar: "" },
{ nama: "ASNIDA YANTI BINTI ANI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F116", blok: "STAR", extension: "04-9882286", email: "asnida933@uitm.edu.my", gambar: "" },
{ nama: "AZIANI BINTI AHMAD", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B1-56", blok: "HEA", extension: "04-9882512", email: "aziani@uitm.edu.my", gambar: "" },
{ nama: "AZLIANA BINTI RAMLI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B1-20", blok: "HEA", extension: "04-9882784", email: "azliana@uitm.edu.my", gambar: "" },
{ nama: "DALINA BINTI SAMSUDIN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "H-06", blok: "H", extension: "04-9882799", email: "dalina@uitm.edu.my", gambar: "" },
{ nama: "FAIEZAH BINTI HASHIM (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F111", blok: "STAR", extension: "04-9882257", email: "faiezahhashim@uitm.edu.my", gambar: "" },
{ nama: "0", jawatan: "0", fakulti: "0", bilik: "F204B", blok: "STAR", extension: "04-9882267", email: "0", gambar: "" },
{ nama: "HANANI BINTI YAZID", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F019", blok: "STAR", extension: "04-9882278", email: "hanani946@uitm.edu.my", gambar: "" },
{ nama: "HELYATI BINTI ABU HASSAN SHAARI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F209", blok: "STAR", extension: "04-9882251", email: "helyati@uitm.edu.my", gambar: "" },
{ nama: "JAMIL BIN TAJAM (Ts DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F216", blok: "STAR", extension: "04-9882264", email: "jamiltajam@uitm.edu.my", gambar: "" },
{ nama: "JEYASHELLY A/P ANDAS (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "G201A", blok: "G", extension: "04-9882569", email: "drshelly@uitm.edu.my", gambar: "" },
{ nama: "KHAIRUNNISA BINTI AHMAD KAMIL (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F106-A", blok: "STAR", extension: "04-9882306", email: "khairunnisakamil@uitm.edu.my", gambar: "" },
{ nama: "KHUZAIMAH BINTI NAZIR (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F210", blok: "STAR", extension: "04-9882281", email: "khuzaimahnazir@uitm.edu.my", gambar: "" },
{ nama: "MADHIYAH BT YAHAYA BERMAKAI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "H-11", blok: "H", extension: "04-9882722", email: "madhiyah@uitm.edu.my", gambar: "" },
{ nama: "MOHAMMAD SAIFULDDIN BIN MOHD AZAMI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "E204-P3-B", blok: "E", extension: "04-9882176", email: "saifulddin@uitm.edu.my", gambar: "" },
{ nama: "MOHD AKMAL BIN HASHIM (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F104-B", blok: "STAR", extension: "04-9882159", email: "akmalhashim@uitm.edu.my", gambar: "" },
{ nama: "MOHD FAUZI BIN ABDULLAH", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B0-17", blok: "HEA", extension: "04-9882737", email: "mohdfauziabd@uitm.edu.my", gambar: "" },
{ nama: "MOHD HAFIZ BIN YAAKOB", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "A307", blok: "H", extension: "04-9882758", email: "hafiz959@uitm.edu.my", gambar: "" },
{ nama: "MOHD LIAS BIN KAMAL", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F227", blok: "STAR", extension: "04-9882282", email: "mohdlias@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD AZHAR BIN ZULKFFLE", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B2-53", blok: "HEA", extension: "04-9882733", email: "azharz@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD ZHARFAN MOHD HALIZAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "E204-P2-A", blok: "E", extension: "04-9882175", email: "zharfan@uitm.edu.my", gambar: "" },
{ nama: "NABILAH AKEMAL BINTI MUHD ZAILANI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F206-A", blok: "STAR", extension: "04-9882310", email: "nabilahakemal@uitm.edu.my", gambar: "" },
{ nama: "NON DAINA BINTI MASDAR (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F108", blok: "STAR", extension: "04-9882298", email: "daina@uitm.edu.my", gambar: "" },
{ nama: "NOOR AISHATUN BINTI MAJID", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "J-06", blok: "J", extension: "04-9882037", email: "nooraishatun@uitm.edu.my", gambar: "" },
{ nama: "NOOR HAFIZAH BINTI UYUP", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "H-08", blok: "H", extension: "04-9882758", email: "hafizah802@uitm.edu.my", gambar: "" },
{ nama: "NOR AZIRA IRMA BINTI MUHAMMAD", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F207", blok: "STAR", extension: "04-9882292", email: "azira_irma@uitm.edu.my", gambar: "" },
{ nama: "NOR HAFIZAH BINTI CHE ISMAIL (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F118", blok: "STAR", extension: "04-9882284", email: "hafizah477@uitm.edu.my", gambar: "" },
{ nama: "NOR MAZLINA BINTI ABDUL WAHAB", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "J-10", blok: "J", extension: "04-9882782", email: "normazlina@uitm.edu.my", gambar: "" },
{ nama: "NOR NAIMAH ROSYADAH AHMAD (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "I-11", blok: "I", extension: "04-9882785", email: "naimahrosyadah@uitm.edu.my", gambar: "" },
{ nama: "NOR SHAFIKAH IDRIS (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B0-28", blok: "HEA", extension: "04-9882868", email: "shafikahidris@uitm.edu.my", gambar: "" },
{ nama: "NORHA BINTI ABDUL HADI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "H-04", blok: "H", extension: "04-9882722", email: "norha.hadi@uitm.edu.my", gambar: "" },
{ nama: "NUR MAISARAH BINTI SARIZAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B1-42", blok: "HEA", extension: "04-9882359", email: "maisarahsarizan@uitm.edu.my", gambar: "" },
{ nama: "NUR NASULHAH BINTI KASIM (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F017", blok: "STAR", extension: "04-9882285", email: "nurnasulhah@uitm.edu.my", gambar: "" },
{ nama: "NUR RAIHAN BINTI MOHAMED (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F209-B", blok: "STAR", extension: "04-9882915", email: "raihanmohamed@uitm.edu.my", gambar: "" },
{ nama: "NURUL AIZAN BINTI MOHD ZAINI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F114", blok: "STAR", extension: "04-9882258", email: "nurulaizan@uitm.edu.my", gambar: "" },
{ nama: "NURUL ZAWANI BINTI ALIAS (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F113", blok: "STAR", extension: "04-9882288", email: "zawani299@uitm.edu.my", gambar: "" },
{ nama: "RIZANA BT YUSOF (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F208", blok: "STAR", extension: "04-9882296", email: "rizana@uitm.edu.my", gambar: "" },
{ nama: "ROSNANI BINTI NAZRI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "E101-P3-A", blok: "E", extension: "04-9882164", email: "rosnani176@uitm.edu.my", gambar: "" },
{ nama: "ROSYAINI BINTI AFINDI ZAMAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F016", blok: "STAR", extension: "04-9882254", email: "rosyaini@uitm.edu.my", gambar: "" },
{ nama: "ROZIANA BINTI MOHAMED HANAPHI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F109", blok: "STAR", extension: "04-9882290", email: "roziana@uitm.edu.my", gambar: "" },
{ nama: "ROZILAH BINTI RAJMI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B2-42", blok: "C", extension: "04-9882752", email: "rozilahrajmi@uitm.edu.my", gambar: "" },
{ nama: "SAIFUL BAHRI BIN MOHD YASIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F133", blok: "-", extension: "04-9882261", email: "saiful926@uitm.edu.my", gambar: "" },
{ nama: "SALAMIAH BINTI ZAKARIA", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "J-03", blok: "J", extension: "04-9882725", email: "salamiah882@uitm.edu.my", gambar: "" },
{ nama: "SARINA BINTI MOHAMAD", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F112", blok: "STAR", extension: "04-9882289", email: "sarin618@uitm.edu.my", gambar: "" },
{ nama: "SHARIZAL BIN HASAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F228", blok: "STAR", extension: "04-9882255", email: "sharizal187@uitm.edu.my", gambar: "" },
{ nama: "SITI NOR BINTI DIN (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F015", blok: "STAR", extension: "04-9882306", email: "sitinor432@uitm.edu.my", gambar: "" },
{ nama: "SITI NURLIA ALI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B1-40", blok: "HEA", extension: "04-9882755", email: "sitinurlia@uitm.edu.my", gambar: "" },
{ nama: "SITI ZULAIKHA MOHD YUSOF (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F204A", blok: "C", extension: "04-9882268", email: "sitizulaikhamy@uitm.edu.my", gambar: "" },
{ nama: "SOLHAN BINTI YAHYA (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B2-43", blok: "HEA", extension: "04-9882152", email: "solhan@uitm.edu.my", gambar: "" },
{ nama: "SUHAIDA DILA BINTI SAFIAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F117", blok: "STAR", extension: "04-9882259", email: "suhaidadila@uitm.edu.my", gambar: "" },
{ nama: "SYARIFAH NURSYIMI AZLINA BINTI SYED ISMAIL", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F115", blok: "STAR", extension: "04-9882287", email: "syarifah_nursyimi@uitm.edu.my", gambar: "" },
{ nama: "TUN MOHD FIRDAUS BIN AZIS (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F104-A", blok: "STAR", extension: "04-9882263", email: "firdaus9219@uitm.edu.my", gambar: "" },
{ nama: "WAHIDA BINTI ABDUL RAHMAN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "I-08", blok: "WH", extension: "04-9882380", email: "wahida811@uitm.edu.my", gambar: "" },
{ nama: "WAN NUR ATIKAH HAJI WAN NAFI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B0-25", blok: "HEA", extension: "04-9882695", email: "atikahnafi@uitm.edu.my", gambar: "" },
{ nama: "ZAIDI BIN AB GHANI (Ts DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "A217", blok: "H", extension: "04-9882773", email: "zaidi433@uitm.edu.my", gambar: "" },
{ nama: "ZAINAB BINTI RAZALI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B0-47", blok: "HEA", extension: "04-9882322", email: "zainab215@uitm.edu.my", gambar: "" },
{ nama: "ZALINA BINTI ZAINAL ABIDIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F010", blok: "STAR", extension: "04-9882252", email: "zalina.za@uitm.edu.my", gambar: "" },
{ nama: "ZULIAHANI BINTI AHMAD (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F007", blok: "STAR", extension: "04-9882591", email: "zuliahani@uitm.edu.my", gambar: "" },
{ nama: "DYIA SYALEYANA BINTI MD SHUKRI", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F214", blok: "H", extension: "04-9882265", email: "dyia839@uitm.edu.my", gambar: "" },
{ nama: "KHAIRUL NAIM BIN ABD AZIZ", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B2-07", blok: "HEA", extension: "04-9882821", email: "khairul87@uitm.edu.my", gambar: "" },
{ nama: "MUHAMAD NAIMAN BIN SARIP", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B2-19", blok: "HEA", extension: "04-9882724", email: "naimansarip@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD AKMAL BIN ROSLANI", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B2-11", blok: "HEA", extension: "04-9882894", email: "akmalroslani@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD SYUKRI BIN NOOR AZMAN", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "C301-P5", blok: "C", extension: "04-9882106", email: "syukriazman@uitm.edu.my", gambar: "" },
{ nama: "NOORSYAM BINTI YUSOF", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "H-03", blok: "H", extension: "04-9882745", email: "noorsyamcy@uitm.edu.my", gambar: "" },
{ nama: "NOR ATIKAH HUSNA BINTI AHMAD NASIR", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "C207-P5", blok: "H", extension: "04-9882184", email: "atikah1388@uitm.edu.my", gambar: "" },
{ nama: "NORLIN BINTI SHUHAIME", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "H-01", blok: "H", extension: "04-9882848", email: "norlin223@uitm.edu.my", gambar: "" },
{ nama: "NUR SYAFIQAH BT RAHIM", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B2-05", blok: "HEA", extension: "04-9882867", email: "syafiqahrahim@uitm.edu.my", gambar: "" },
{ nama: "ROHAYU BINTI RAMLI", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B1-35", blok: "HEA", extension: "04-9882364", email: "rohayu@uitm.edu.my", gambar: "" },
{ nama: "SHAFINAS BINTI ABDULLAH", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F106-B", blok: "STAR", extension: "04-9882313", email: "sshafi6359@uitm.edu.my", gambar: "" },
{ nama: "SHARIFAH NAFISAH BINTI SYED ISMAIL", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "J-07", blok: "J", extension: "04-9882701", email: "sharifahnafisah@uitm.edu.my", gambar: "" },
{ nama: "SHARIR AIZAT BIN KAMARUDDIN", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "C207-P4-A", blok: "C", extension: "04-9882157", email: "shariraizat@uitm.edu.my", gambar: "" },
{ nama: "SITI HAJAR BINTI MOHMAD SALLEH", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "H-10", blok: "H", extension: "04-9882867", email: "sitiha2902@uitm.edu.my", gambar: "" },
{ nama: "SITI NOORASHIKIN BINTI JAMAL", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "I-07", blok: "WH", extension: "04-9882592", email: "snoorashikin743@uitm.edu.my", gambar: "" },
{ nama: "YUSWANIE BINTI MD YUSOF", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "F206-B", blok: "STAR", extension: "04-9882610", email: "yuswanie824@uitm.edu.my", gambar: "" },
{ nama: "ZAMZILA ERDAWATI BINTI ZAINOL", jawatan: "PENSYARAH", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "B1-01", blok: "HEA", extension: "04-9882807", email: "zamzila396@uitm.edu.my", gambar: "" },
{ nama: "MOHD SYAMAIZAR BIN MUSTAFA", jawatan: "P.EKSEKUTIF KANAN", fakulti: "Fakulti Sains Gunaan (FSG)", bilik: "C207-P6", blok: "C", extension: "04-9882185", email: "syamaizar@uitm.edu.my", gambar: "" },
{ nama: "CHUAH TSE SENG (Prof DR)", jawatan: "PROFESOR", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "F204", blok: "STAR", extension: "04-9882279", email: "chuahts@uitm.edu.my", gambar: "" },
{ nama: "KHAIRUN NISA BINTI KAMARUDDIN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "F213", blok: "STAR", extension: "04-9882293", email: "khairunnk@uitm.edu.my", gambar: "" },
{ nama: "MOHAMMAD AZIZI BIN ABDULLAH", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B0-16", blok: "HEA", extension: "04-9882873", email: "azizi@uitm.edu.my", gambar: "" },
{ nama: "MOHD SAIFUL AKBAR B MOHAMAD SAHAL", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B0-15", blok: "HEA", extension: "04-9882713", email: "msaifulakbar@uitm.edu.my", gambar: "" },
{ nama: "NAJIHAH FARHAN BINTI SABRI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "F107", blok: "STAR", extension: "04-9882312", email: "najihahfs@uitm.edu.my", gambar: "" },
{ nama: "NAZALYYUSSMA BINTI YUSOP", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "F018", blok: "STAR", extension: "04-9882297", email: "nazalyyussma@uitm.edu.my", gambar: "" },
{ nama: "NOOR ZUHAIRAH BINTI SAMSUDDIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "F104-C", blok: "STAR", extension: "04-9882256", email: "zuhairah445@uitm.edu.my", gambar: "" },
{ nama: "NORHANANI BINTI AHMAD", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B2-15", blok: "HEA", extension: "04-9882712", email: "norhanani615@uitm.edu.my", gambar: "" },
{ nama: "NUR FAEZAH BT OMAR (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B1-69", blok: "HEA", extension: "04-9882865", email: "nurfaezah@uitm.edu.my", gambar: "" },
{ nama: "NURUL FATIHAH BINTI ABD LATIP (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "F211", blok: "STAR", extension: "04-9882281", email: "nurulfatihahabdlatip@uitm.edu.my", gambar: "" },
{ nama: "KHAIRUN NISAA' BINTI MOHD NOR", jawatan: "PENSYARAH", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B1-15", blok: "HEA", extension: "04-9882691", email: "khairunnisaa@uitm.edu.my", gambar: "" },
{ nama: "MARLIA BINTI MUSA", jawatan: "PENSYARAH", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B2-63", blok: "HEA", extension: "04-9882621", email: "marliamusa@uitm.edu.my", gambar: "" },
{ nama: "MOHD ASHRAF ZAINOL ABIDIN", jawatan: "PENSYARAH", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B0-26", blok: "HEA", extension: "04-9882874", email: "ashrafzainol@uitm.edu.my", gambar: "" },
{ nama: "NORMADHIYAH BINTI ROSLAN", jawatan: "PENSYARAH", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "E104-P5", blok: "E", extension: "04-9882179", email: "normardhiyah@uitm.edu.my", gambar: "" },
{ nama: "NUR FIRDAUS BT ABDUL RASHID", jawatan: "PENSYARAH", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B2-14", blok: "HEA", extension: "04-9882887", email: "nurfirdaus@uitm.edu.my", gambar: "" },
{ nama: "NUR ILLANI BINTI ABDUL RAZAK", jawatan: "PENSYARAH", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B2-23", blok: "HEA", extension: "04-9882870", email: "illanirazak@uitm.edu.my", gambar: "" },
{ nama: "NURHALIZA BT MOHAMAD SHAHIDIN", jawatan: "PENSYARAH", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "B2-59", blok: "HEA", extension: "04-9882726", email: "nurhaliza925@uitm.edu.my", gambar: "" },
{ nama: "MOHAMAD REDZUANDI BIN ABDUL RAHIM", jawatan: "PEN. JURUTERA", fakulti: "Fakulti Perladangan & Agroteknologi (FPA)", bilik: "Bgkel DPIM", blok: "", extension: "04-9882435", email: "m_redzuandi@uitm.edu.my", gambar: "" },
{ nama: "AZRUL BIN ABDULLAH (DR.)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Perakaunan (FP)", bilik: "B2-10", blok: "HEA", extension: "04-9882666", email: "azrul229@uitm.edu.my", gambar: "" },
{ nama: "AZURA BT MOHD NOOR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B0-52", blok: "HEA", extension: "04-9882686", email: "azura@uitm.edu.my", gambar: "" },
{ nama: "FAZNI BINTI MOHAMAD FADZILLAH", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B0-56", blok: "HEA", extension: "04-9882854", email: "faznimf@uitm.edu.my", gambar: "" },
{ nama: "MARJAN BINTI MOHD NOOR (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B1-50", blok: "HEA", extension: "04-9882766", email: "marjan@uitm.edu.my", gambar: "" },
{ nama: "MASTURA MALIK@MALEK (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B1-51", blok: "", extension: "04-9882835", email: "masturahmalek@uitm.edu.my", gambar: "" },
{ nama: "NADZIR BIN AWANG AHMAD @ SAID", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B1-48", blok: "HEA", extension: "04-9882884", email: "nadzir@uitm.edu.my", gambar: "" },
{ nama: "NAZIRAH NAIIMI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B1-47", blok: "HEA", extension: "04-9882801", email: "nazirahnaiimi@uitm.edu.my", gambar: "" },
{ nama: "NOR KARTINI BINTI MOHD RODZI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B1-46", blok: "HEA", extension: "04-9882817", email: "norkartini@uitm.edu.my", gambar: "" },
{ nama: "NORIZAM BT AHMAD @ MUHAMMAD", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B0-64", blok: "HEA", extension: "04-9882876", email: "norizam@uitm.edu.my", gambar: "" },
{ nama: "ROSLIDA RAMLEE", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B0-49", blok: "", extension: "04-9882878", email: "roslidar@uitm.edu.my", gambar: "" },
{ nama: "NOR HASHIMAH ABDUL WAHID", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Perakaunan (FP)", bilik: "B0-45", blok: "", extension: "04-9882814", email: "norawuitm@uitm.edu.my", gambar: "" },
{ nama: "FA'IZAH BT GHAZI", jawatan: "PENSYARAH", fakulti: "Fakulti Perakaunan (FP)", bilik: "B0-62", blok: "HEA", extension: "04-9882859", email: "faizahghazi@uitm.edu.my", gambar: "" },
{ nama: "NURUL IZZAH IZZATI ROSLI", jawatan: "PENSYARAH", fakulti: "Fakulti Perakaunan (FP)", bilik: "E104-P4-A", blok: "E", extension: "04-9882169", email: "izzahhrosli@uitm.edu.my", gambar: "" },
{ nama: "SITI NOR SYAHIRA SHAIKH MOHAMAD", jawatan: "PENSYARAH", fakulti: "Fakulti Perakaunan (FP)", bilik: "E104-P4-B", blok: "E", extension: "04-9882169", email: "sitinorsyahira@uitm.edu.my", gambar: "" },
{ nama: "AHMAD NIZAN BIN MAT NOOR (PM DR.)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "F219", blok: "HEA", extension: "04-9882476", email: "ahmadnizan@uitm.edu.my", gambar: "" },
{ nama: "MAHYUDIN BIN AHMAD (PM DR)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-75", blok: "HEA", extension: "04-9882358", email: "mahyudin@uitm.edu.my", gambar: "" },
{ nama: "RABEATUL HUSNA ABDUL RAHMAN (PM DR)", jawatan: "PROFESOR MADYA", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B2-33", blok: "HEA", extension: "04-9882670", email: "rabeatulhusna@uitm.edu.my", gambar: "" },
{ nama: "ATHIFAH NAJWANI BINTI SHAHIDAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "I-06", blok: "", extension: "04-9882683", email: "athifahnajwani@uitm.edu.my", gambar: "" },
{ nama: "CHEN JEN EEM (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-11", blok: "HEA", extension: "04-9882738", email: "jechen@uitm.edu.my", gambar: "" },
{ nama: "ELIY NAZIRA BINTI MAT NAZIR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-37", blok: "HEA", extension: "04-9882795", email: "eliy083@uitm.edu.my", gambar: "" },
{ nama: "FADLI FIZARI BIN ABU HASSAN ASARI (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "H-00", blok: "H", extension: "04-9882758", email: "fizari754@uitm.edu.my", gambar: "" },
{ nama: "FARAH LINA AZIZAN (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-12", blok: "HEA", extension: "04-9882741", email: "farahlina@uitm.edu.my", gambar: "" },
{ nama: "HAIRULNIZA ABD RAHMAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B2-02", blok: "HEA", extension: "04-9882810", email: "hairulniza@uitm.edu.my", gambar: "" },
{ nama: "HASYEILLA BINTI ABD MUTALIB (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-01", blok: "HEA", extension: "04-9882730", email: "hasyeilla798@uitm.edu.my", gambar: "" },
{ nama: "IMA ILYANI BINTI IBRAHIM", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-66", blok: "HEA", extension: "04-9882845", email: "ilyani686@uitm.edu.my", gambar: "" },
{ nama: "IMRAN KHUSAIRI SHAFEE (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-03", blok: "HEA", extension: "04-9882893", email: "imrankhusairi@uitm.edu.my", gambar: "" },
{ nama: "ISMALAILI BINTI ISMAIL (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-65", blok: "HEA", extension: "04-9882861", email: "ismalaili007@uitm.edu.my", gambar: "" },
{ nama: "MOHAMAD NIZA BIN MD NOR", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-50", blok: "HEA", extension: "04-9882832", email: "mohdniza@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD AIMAN ARIFIN (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "E101-P6", blok: "E", extension: "04-9882162", email: "aimanarifin@uitm.edu.my", gambar: "" },
{ nama: "MUTIIAH MOHAMAD (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B2-25", blok: "HEA", extension: "04-9882871", email: "mutiiah@uitm.edu.my", gambar: "" },
{ nama: "NIK AZLINA BINTI NIK ABDULLAH", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-48", blok: "HEA", extension: "04-9882523", email: "nikazlina@uitm.edu.my", gambar: "" },
{ nama: "NOOR AZREEN MOHD KHUSHAIRI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-73", blok: "HEA", extension: "04-9882150", email: "azreenmk@uitm.edu.my", gambar: "" },
{ nama: "NOOR HAFIZHA BINTI MUHAMAD YUSUF", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-04", blok: "HEA", extension: "04-9882697", email: "hafizha853@uitm.edu.my", gambar: "" },
{ nama: "NOOR SHARIDA BINTI BADRI SHAH", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-08", blok: "HEA", extension: "04-9882609", email: "sharida699@uitm.edu.my", gambar: "" },
{ nama: "NOR ANIS BINTI SHAFAI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-02", blok: "HEA", extension: "04-9882882", email: "anis448@uitm.edu.my", gambar: "" },
{ nama: "NORAINI BINTI NASIRUN @ HIRUN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-67", blok: "HEA", extension: "04-9882717", email: "noraini305@uitm.edu.my", gambar: "" },
{ nama: "NORALIYATI BINTI ZAKARIA (DATIN)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-12", blok: "HEA", extension: "04-9882361", email: "noraliyati@uitm.edu.my", gambar: "" },
{ nama: "NORHISAM BIN BULOT (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-27", blok: "HEA", extension: "04-9882734", email: "norhisam@uitm.edu.my", gambar: "" },
{ nama: "NORSHAMSHINA BINTI MAT ISA (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B2-09", blok: "HEA", extension: "04-9882794", email: "norshamshina@uitm.edu.my", gambar: "" },
{ nama: "NUR ZAINIE BINTI ABD HAMID (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-10", blok: "HEA", extension: "04-9882318", email: "nurzainie60@uitm.edu.my", gambar: "" },
{ nama: "NURSYAMILAH ANNUAR (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B2-18", blok: "HEA", extension: "04-9882711", email: "nsyamilah@uitm.edu.my", gambar: "" },
{ nama: "NURUL LABANIHUDA BT ABDUL RAHMAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B2-06", blok: "HEA", extension: "04-9882797", email: "labanihuda@uitm.edu.my", gambar: "" },
{ nama: "NURWAHIDA BINTI FUAD (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-05", blok: "HEA", extension: "04-9882718", email: "wahida.fuad@uitm.edu.my", gambar: "" },
{ nama: "ROZIHANIM BT SHEKH ZAIN", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-07", blok: "HEA", extension: "04-9882864", email: "rozihanim@uitm.edu.my", gambar: "" },
{ nama: "SABIROH BINTI MD SABRI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-06", blok: "HEA", extension: "04-9882356", email: "sabir707@uitm.edu.my", gambar: "" },
{ nama: "SHAFIQ BIN SHAHRUDDIN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "F212", blok: "STAR", extension: "04-9882265", email: "shafiqshahruddin@uitm.edu.my", gambar: "" },
{ nama: "SHALIZA AZREEN BINTI MOHD ZULKIFLI", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-10", blok: "HEA", extension: "04-9882625", email: "shaliza@uitm.edu.my", gambar: "" },
{ nama: "SHAMSHUL ANAZ B KASSIM (DR.)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-04", blok: "HEA", extension: "04-9882699", email: "shamsulanaz@uitm.edu.my", gambar: "" },
{ nama: "SHARIFAH KHAIROL MUSAIRAH SYED ABDUL MUTALIB (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-07", blok: "HEA", extension: "04-9882665", email: "skmusairah@uitm.edu.my", gambar: "" },
{ nama: "SITI NUR ZAHIRAH OMAR (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "C301-P6", blok: "E", extension: "04-9882178", email: "sitinurzahirah@uitm.edu.my", gambar: "" },
{ nama: "SYAZWANI BINTI YA", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B2-04", blok: "HEA", extension: "04-9882747", email: "syazwani446@uitm.edu.my", gambar: "" },
{ nama: "WAN 'ALIAA WAN ANIS (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "E101-P5", blok: "HEA", extension: "04-9882180", email: "wanaliaa@uitm.edu.my", gambar: "" },
{ nama: "WAN MOHD YASEER BIN MOHD ABDOH", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-27", blok: "HEA", extension: "04-9882789", email: "wanmohdyaseer@uitm.edu.my", gambar: "" },
{ nama: "ZULAIHA BINTI AHMAD", jawatan: "PENSYARAH KANAN", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-02", blok: "HEA", extension: "04-9882519", email: "zulaiha895@uitm.edu.my", gambar: "" },
{ nama: "ABDUL HAFIZ BIN YUSOF", jawatan: "PENSYARAH", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-09", blok: "HEA", extension: "04-9882862", email: "hafiz459@uitm.edu.my", gambar: "" },
{ nama: "NURUL FARIHIN BINTI MHD NASIR", jawatan: "PENSYARAH", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B1-53", blok: "HEA", extension: "04-9882767", email: "nurulfarihin@uitm.edu.my", gambar: "" },
{ nama: "ZUNAIRAH BINTI HASAN", jawatan: "PENSYARAH", fakulti: "Fakulti Pengurusan Perniagaan (FPP)", bilik: "B0-13", blok: "HEA", extension: "04-9882798", email: "zunairah@uitm.edu.my", gambar: "" },
{ nama: "AFIFFUDIN BIN MOHAMMED NOOR (PROF MADYA DR)", jawatan: "PROFESOR MADYA", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B0-37", blok: "HEA", extension: "04-9882510", email: "afiffudin@uitm.edu.my", gambar: "" },
{ nama: "AZHAR BIN ABDUL RAHMAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B0-43", blok: "HEA", extension: "04-9882869", email: "azharabdulrahman@uitm.edu.my", gambar: "" },
{ nama: "DR NURUL FARHANA YAHAYA", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "E204-P6", blok: "HEA", extension: "04-9882000", email: "nfarhanay@uitm.edu.my", gambar: "" },
{ nama: "MARINA ABU BAKAR (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B0-39", blok: "HEA", extension: "04-9882786", email: "marinaab@uitm.edu.my", gambar: "" },
{ nama: "NADIYAH BINTI HASHIM", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B1-44", blok: "HEA", extension: "04-9882727", email: "nadiyah@uitm.edu.my", gambar: "" },
{ nama: "NOOR AZURA BINTI ZAINUDDIN", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B1-41", blok: "HEA", extension: "04-9882720", email: "noorazura@uitm.edu.my", gambar: "" },
{ nama: "NORAINI BINTI ISMAIL (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B0-42", blok: "HEA", extension: "04-9882877", email: "noraini045@uitm.edu.my", gambar: "" },
{ nama: "NUR FATIN NABILAH SHAHROM (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B2-55", blok: "HEA", extension: "04-9882748", email: "fatinnabilahshahrom@uitm.edu.my", gambar: "" },
{ nama: "NURLIYANA MOHD TALIB (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B0-41", blok: "HEA", extension: "04-9882615", email: "liyanatalib@uitm.edu.my", gambar: "" },
{ nama: "SOLIHAH BINTI YAHYA ZIKRI", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "C201-P2-A", blok: "C", extension: "04-9882151", email: "solihah86@uitm.edu.my", gambar: "" },
{ nama: "SYAIMAK BINTI ISMAIL @ MAT YUSOFF (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B0-40", blok: "HEA", extension: "04-9882750", email: "syaimak@uitm.edu.my", gambar: "" },
{ nama: "ZURAIMY BIN ALI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "B0-38", blok: "HEA", extension: "04-9882706", email: "zuraimy@uitm.edu.my", gambar: "" },
{ nama: "MUHAMMAD MUKHLIS MUHAMMAD ROSLI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Islam Kontemporari (ACIS)", bilik: "E204-P4-A", blok: "E", extension: "04-9882177", email: "mukhlisrosli@uitm.edu.my", gambar: "" },
{ nama: "LATISHA ASMAAK BT SHAFIE (PROF. MADYA DR)", jawatan: "PROFESOR MADYA", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "F104", blok: "HEA", extension: "04-9882269", email: "ciklatisha@uitm.edu.my", gambar: "" },
{ nama: "MOHAMAD FADHILI B YAHAYA (PROF MADYA DR)", jawatan: "PROFESOR MADYA", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "F206", blok: "STAR", extension: "04-9882276", email: "mohdfadhili@uitm.edu.my", gambar: "" },
{ nama: "NAGIDAR KAUR @ NAGINDER KAUR SURJIT SINGH (DR)", jawatan: "PROFESOR MADYA", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-29", blok: "HEA", extension: "04-9882796", email: "ninder@uitm.edu.my", gambar: "" },
{ nama: "ABDUL BASIR BIN AWANG @ MOHD RAMLI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-30", blok: "HEA", extension: "04-9882826", email: "abasir180@uitm.edu.my", gambar: "" },
{ nama: "ADI AFZAL BIN AHMAD", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B2-29", blok: "HEA", extension: "04-9882354", email: "adi_afzal@uitm.edu.my", gambar: "" },
{ nama: "AMIZURA HANADI BINTI MOHD RADZI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B2-22", blok: "HEA", extension: "04-9882881", email: "amizura@uitm.edu.my", gambar: "" },
{ nama: "ANIS BT MAESIN", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-30", blok: "HEA", extension: "04-9882846", email: "anismaesin@uitm.edu.my", gambar: "" },
{ nama: "BADRUL HISHAM BIN AHMAD", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B2-30", blok: "HEA", extension: "04-9882849", email: "badrulhisham@uitm.edu.my", gambar: "" },
{ nama: "CHAN SWEE KAI", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B2-31", blok: "HEA", extension: "04-9882898", email: "skchan@uitm.edu.my", gambar: "" },
{ nama: "FAZMAWATI BINTI ZAKARIA", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-34", blok: "HEA", extension: "04-9882811", email: "fazmawati@uitm.edu.my", gambar: "" },
{ nama: "KASMAWATI ZAKARIA (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-35", blok: "HEA", extension: "04-9882700", email: "kasmawatizakaria@uitm.edu.my", gambar: "" },
{ nama: "MAHANI BINTI MANSOR", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-33", blok: "HEA", extension: "04-9882827", email: "mahani@uitm.edu.my", gambar: "" },
{ nama: "MAJDAH BINTI CHULAN", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-53", blok: "HEA", extension: "04-9882866", email: "majdah@uitm.edu.my", gambar: "" },
{ nama: "MARCIA JANE A/P GANASAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "E201-P5", blok: "E", extension: "04-9882102", email: "marcia@uitm.edu.my", gambar: "" },
{ nama: "NADHILAH BT ABDUL PISAL (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-14", blok: "HEA", extension: "04-9882694", email: "nadhilah@uitm.edu.my", gambar: "" },
{ nama: "NAZIRA BINTI OSMAN (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B2-34", blok: "HEA", extension: "04-9882800", email: "naziraosman@uitm.edu.my", gambar: "" },
{ nama: "NOORAZALIA IZHA BINTI HARON", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-34", blok: "HEA", extension: "04-9882685", email: "noorazalia177@uitm.edu.my", gambar: "" },
{ nama: "NOR ALIFAH BINTI ROSAIDI", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "J-01", blok: "J", extension: "04-9882709", email: "alifah.rosaidi@uitm.edu.my", gambar: "" },
{ nama: "NOR AZIRA BINTI MOHD RADZI", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-44", blok: "HEA", extension: "04-9882682", email: "norazira202@uitm.edu.my", gambar: "" },
{ nama: "NORHAJAWATI BT ABDUL HALIM", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-31", blok: "HEA", extension: "04-9882668", email: "norhajawati@uitm.edu.my", gambar: "" },
{ nama: "NORLIZAWATI BINTI GHAZALI", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-32", blok: "HEA", extension: "04-9882816", email: "norlizawati@uitm.edu.my", gambar: "" },
{ nama: "RAZLINA BINTI RAZALI (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-33", blok: "HEA", extension: "04-9882828", email: "razlinarazali@uitm.edu.my", gambar: "" },
{ nama: "SITI SARINA BINTI SULAIMAN", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-16", blok: "HEA", extension: "04-9882860", email: "sitisarina@uitm.edu.my", gambar: "" },
{ nama: "SURINA BT NAYAN", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B0-32", blok: "HEA", extension: "04-9882792", email: "surinana@uitm.edu.my", gambar: "" },
{ nama: "UMMI SYARAH BINTI ISMAIL (DR)", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-29", blok: "HEA", extension: "04-9882788", email: "ummi@uitm.edu.my", gambar: "" },
{ nama: "YANG SALEHAH BINTI ABDULLAH SANI", jawatan: "PENSYARAH KANAN", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-23", blok: "HEA", extension: "04-9882611", email: "yangsalehah@uitm.edu.my", gambar: "" },
{ nama: "AFIFAH AZMI", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-36", blok: "HEA", extension: "04-9882772", email: "afifah169@uitm.edu.my", gambar: "" },
{ nama: "CHEE SIE CHING", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "E204-P5", blok: "E", extension: "04-9882101", email: "cheesieching@uitm.edu.my", gambar: "" },
{ nama: "FADHLINA CHE ARSHAD", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "E101-P1-A", blok: "E", extension: "04-9882162", email: "2026136171@student.uitm.edu.my", gambar: "" },
{ nama: "HUZAIFAH BT A HAMID", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B2-12", blok: "HEA", extension: "04-9882836", email: "huzaifahhamid@uitm.edu.my", gambar: "" },
{ nama: "NAZRIN AFIF ABU SUFFIAN", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "C301-P3-A", blok: "c", extension: "04-9882160", email: "nazrinafif@uitm.edu.my", gambar: "" },
{ nama: "NUR ASIAH SYAFIKAH MOHAMAD SAZALI", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "I-12", blok: "I", extension: "04-9882077", email: "asiahsyafikah@uitm.edu.my", gambar: "" },
{ nama: "NUR FAIRUZ WAHIDA BINTI IBRAHIM", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B2-32", blok: "HEA", extension: "04-9882844", email: "fairuz427@uitm.edu.my", gambar: "" },
{ nama: "NUR SYAZWANI BINTI HALIM", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "E104-P1", blok: "-", extension: "04-9882166", email: "syaz@uitm.edu.my", gambar: "" },
{ nama: "RAISA RASTOM", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "C301-P2-B", blok: "C", extension: "04-9882159", email: "raisa@uitm.edu.my", gambar: "" },
{ nama: "SAEIDAH BINTI MALIK @ MALEK", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "B1-31", blok: "HEA", extension: "04-9882804", email: "saeidah@uitm.edu.my", gambar: "" },
{ nama: "NORSHAHIRA ISMAIL", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "E204-P1-A", blok: "E", extension: "04-9882174", email: "norshahira@uitm.edu.my", gambar: "" },
{ nama: "ANIS MARDHIAH AHMAD KHAIRUDDIN", jawatan: "PENSYARAH", fakulti: "Akademi Pengajian Bahasa (APB)", bilik: "C301-P2-A", blok: "C", extension: "04-9882159", email: "anismardhiah@uitm.edu.my", gambar: "" },
        ];

        // Rujukan Elemen DOM
        const searchInput = document.getElementById('searchInput');
        const mainContainer = document.getElementById('main-container');
        const resultsContainer = document.getElementById('results-container');
        const resultsList = document.getElementById('results-list');
        const resultsCount = document.getElementById('results-count');
        const clearBtn = document.getElementById('clearBtn');
        const logoContainer = document.getElementById('logo-container');

        // Fungsi mengubah URL Google Drive supaya boleh menjadi sumber <img> secara terus
        function getDirectImageUrl(url) {
            if (!url) return '';
            
            // Format Google Drive view link
            if (url.includes('drive.google.com/file/d/')) {
                const match = url.match(/\/d\/(.*?)\//);
                if (match && match[1]) {
                    return `https://drive.google.com/uc?export=view&id=${match[1]}`;
                }
            }
            return url;
        }

        // Fungsi membina gambar Dummy/Anonymous (menggunakan ui-avatars berdasarkan nama)
        function getDummyAvatar(name) {
            const cleanName = encodeURIComponent(name.replace(/\([^)]*\)/g, '').trim());
            return `https://ui-avatars.com/api/?name=${cleanName}&background=f3f4f6&color=374151&size=150&bold=true`;
        }

        // Fungsi memaparkan keputusan
        function renderResults(results) {
            resultsList.innerHTML = ''; // Kosongkan senarai sedia ada
            
            if (results.length === 0) {
                resultsCount.innerText = "Tiada keputusan ditemui.";
                return;
            }

            resultsCount.innerText = `Kira-kira ${results.length} hasil carian (0.01 saat)`;

            results.forEach(person => {
                // Konfigurasi imej
                const directImgUrl = getDirectImageUrl(person.gambar);
                const dummyImgUrl = getDummyAvatar(person.nama);
                const finalImgSrc = directImgUrl !== '' ? directImgUrl : dummyImgUrl;

                // Bina kad HTML
                const card = document.createElement('div');
                card.className = "flex flex-col md:flex-row gap-6 p-4 rounded-xl hover:bg-gray-50 transition-colors border border-transparent hover:border-gray-200";
                
                card.innerHTML = `
                    <div class="flex-shrink-0 mx-auto md:mx-0">
                        <!-- onerror diletakkan sekiranya directImgUrl gagal (cth: pautan GDrive tidak public) -->
                        <img src="${finalImgSrc}" onerror="this.onerror=null; this.src='${dummyImgUrl}';" alt="Gambar ${person.nama}" class="w-24 h-24 md:w-32 md:h-32 rounded-full object-cover shadow-sm border border-gray-200">
                    </div>
                    <div class="flex-grow flex flex-col justify-center text-center md:text-left">
                        <h2 class="text-xl md:text-2xl font-medium text-blue-700 hover:underline cursor-pointer mb-1">${person.nama}</h2>
                        <div class="text-sm text-gray-600 mb-2 space-x-2">
                            <span class="inline-block bg-blue-100 text-blue-800 px-2 py-1 rounded text-xs font-semibold">${person.jawatan}</span>
                            <span class="inline-block text-gray-500 font-medium">${person.fakulti}</span>
                        </div>
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-2 text-sm text-gray-700 mt-2">
                            <div class="flex items-center justify-center md:justify-start gap-2">
                                <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path></svg>
                                <span>Bilik: <strong>${person.bilik}</strong> (Blok ${person.blok})</span>
                            </div>
                            <div class="flex items-center justify-center md:justify-start gap-2">
                                <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                                <span>Ext: <strong>${person.extension}</strong></span>
                            </div>
                            <div class="flex items-center justify-center md:justify-start gap-2 md:col-span-2">
                                <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                                <a href="mailto:${person.email}" class="text-blue-600 hover:underline">${person.email}</a>
                            </div>
                        </div>
                    </div>
                `;
                
                resultsList.appendChild(card);
            });
        }

        // Fungsi carian
        function handleSearch() {
            const query = searchInput.value.toLowerCase().trim();
            
            // Urus antaramuka (UI transition)
            if (query.length > 0) {
                mainContainer.classList.remove('search-center');
                mainContainer.classList.add('search-top');
                logoContainer.classList.add('hidden'); // Sembunyikan logo besar
                resultsContainer.classList.remove('hidden');
                clearBtn.classList.remove('hidden');
            } else {
                mainContainer.classList.add('search-center');
                mainContainer.classList.remove('search-top');
                logoContainer.classList.remove('hidden');
                resultsContainer.classList.add('hidden');
                clearBtn.classList.add('hidden');
                return; // Berhenti jika kosong
            }

            // Logik tapisan data
            const filteredData = pensyarahData.filter(p => {
                return (
                    (p.nama && p.nama.toLowerCase().includes(query)) ||
                    (p.jawatan && p.jawatan.toLowerCase().includes(query)) ||
                    (p.fakulti && p.fakulti.toLowerCase().includes(query)) ||
                    (p.bilik && p.bilik.toLowerCase().includes(query)) ||
                    (p.email && p.email.toLowerCase().includes(query))
                );
            });

            renderResults(filteredData);
        }

        // Pendengar Acara (Event Listeners)
        searchInput.addEventListener('input', handleSearch);
        
        clearBtn.addEventListener('click', () => {
            searchInput.value = '';
            handleSearch();
            searchInput.focus();
        });

    </script>
</body>
</html>
