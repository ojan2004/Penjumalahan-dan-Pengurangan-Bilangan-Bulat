<html>
 <head>
  <title>
   Matematika
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
   nav {
    position: sticky;
    position: -webkit-sticky;
    top: 0;
    background-color: aliceblue;
    z-index: 1;
    border-bottom: 1px solid rgb(3, 3, 3);
        }
        nav a {
      color: #ffffff;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #d1fae5;
    }
    .btn-primary {
      background-color: #22c55e;
      color: white;
      padding: 10px 20px;
      border-radius: 50px;
      transition: transform 0.2s, background-color 0.3s;
    }
    .btn-primary:hover {
      background-color: #15803d;
      transform: scale(1.1);
    }
    header {
      position: relative;
      text-align: center;
    }
    header img {
      filter: brightness(75%);
    }
    header h1 {
      animation: fadeInDown 2s ease-in-out;
      color:#22c55e;
    }
    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-50px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    ul.list-disc li {
      padding-left: 1rem;
    }
  </style>
 </head>
 <body class="bg-gray-100">
  <!-- Header -->
  <nav class="bg-white shadow-md">
    <div class="container mx-auto px-4 py-2 flex justify-between items-center">
     <a class="text-2xl font-bold text-green-500" href="#">
      MATEMATIKA
     </a>
     <ul class="flex space-x-6"; text-align="right">
      <li>
       <a class="text-gray-700" href="Home.html" >
        Home
       </a>
      </li>
      <li>
       <a class="text-gray-700" href="materi.html">
        Materi
       </a>
      </li>
      <li>
       <a class="text-gray-700" href="Latihan.html">
        Latihan
       </a>
      </li>
     </ul>
     <a class="bg-green-500 text-white px-4 py-2 rounded" href="#">
      Get Started
     </a>
    </div>
   </nav>
   <header class="relative">
    <img alt="unram" class="w-full h-96 object-cover" height="600" src="unram.jpeg" width="1920"/>
    <div class="absolute inset-0 bg-black opacity-50">
    </div>
    <div class="absolute inset-0 flex flex-col justify-center items-center text-center text-white px-4">
     <h1 class="text-4xl md:text-5xl font-bold ">
      Selamat Datang Di Ruang Belajar Matematika
     </h1>
     <p class="mt-4 text-lg md:text-xl">
      Pendidikan Matematika FKIP Universitas Mataram
     </p>
     <a class="mt-6 bg-white text-black px-6 py-3 rounded-full" href="#">
      Get Started
     </a>
    </div>
   </header>
  <!-- Main Content -->
  <main class="container mx-auto px-4 py-16">
   <div class="flex flex-col md:flex-row items-center">
    <div class="md:w-2/3">
     <h2 class="text-2xl font-bold mb-4">
      Ruang Belajar Matematika
     </h2>
     <p class="mb-4">
      Situs web yang dirancang khusus untuk membantu siswa belajar dan memahami konsep-konsep matematika secara interaktif. Platform ini menyediakan berbagai materi pelajaran, soal latihan, video pembelajaran, hingga fitur evaluasi diri yang memungkinkan pengguna belajar secara mandiri dan terstruktur. Dengan memanfaatkan teknologi digital, ruang belajar matematika dapat diakses kapan saja dan di mana saja, memberikan fleksibilitas serta pengalaman belajar yang lebih menarik melalui visualisasi konsep dan penggunaan alat bantu interaktif. Platform ini juga dilengkapi dengan komunitas belajar yang memungkinkan kolaborasi antar pengguna dan bimbingan dari tutor profesional. Adapun fungsi dari platform ini antara lain:
     </p>
     <ul class="list-disc list-inside mb-4">
      <li class="flex items-center mb-2">
       <i class="fas fa-check-circle text-green-600 mr-2">
       </i>
       Akses Materi yang Lebih Luas
      </li>
      <p>Platform digital menyediakan akses ke berbagai macam materi, mulai dari teori dasar hingga materi lanjutan. Sumber daya ini dapat mencakup video tutorial, modul interaktif, soal latihan, dan e-book, yang semuanya dapat diakses kapan saja dan di mana saja.</p>
      <li class="flex items-center mb-2">
       <i class="fas fa-check-circle text-green-600 mr-2">
       </i>
       Latihan Soal Interaktif
      </li>
      <p>Banyak platform menyediakan latihan soal interaktif dengan pembahasan langsung. Siswa dapat langsung mengetahui apakah jawabannya benar atau salah, serta memahami cara penyelesaiannya. Ini memungkinkan siswa untuk belajar dari kesalahan mereka secara langsung.</p>
      <li class="flex items-center mb-2">
       <i class="fas fa-check-circle text-green-600 mr-2">
       </i>
       Pembelajaran Personal
      </li>
      <p>Dengan sistem adaptif yang disertakan dalam beberapa platform, materi dapat disesuaikan dengan kebutuhan dan kemampuan masing-masing siswa. Hal ini memungkinkan pembelajaran yang lebih personal dan efisien.</p>
      <li class="flex items-center mb-2">
        <i class="fas fa-check-circle text-green-600 mr-2">
        </i>
        Visualisasi dan Simulasi
       </li>
       <p>Dalam matematika, beberapa konsep abstrak bisa sulit dipahami tanpa visualisasi. Platform digital sering kali menyediakan alat untuk visualisasi grafik, diagram.</p>
     </ul>
    </div>
    <div class="md:w-1/3 mt-8 md:mt-0 md:ml-8">
     <img alt="siswa" class="rounded shadow" height="300" src="siswa.jpg" width="400" />
    </div>
   </div>
  </main>
  <!-- Footer -->
  <footer class="bg-white py-8">
   <div class="container mx-auto px-4">
    <div class="flex flex-col md:flex-row justify-between">
     <div class="mb-8 md:mb-0">
      <h3 class="text-lg font-bold mb-2">
       UNRAM
      </h3>
      <p>
       Jln. Majapahit No.62
       <br/>
       Universitas Mataram
      </p>
      <p>
       Phone: 087860834277
       <br/>
       Email: pauzanhakim123@gmail.com
      </p>
     </div>
     <div class="mb-8 md:mb-0">
      <h3 class="text-lg font-bold mb-2">
       Partners
      </h3>
      <ul>
       <li>
        <a class="text-gray-600 hover:text-green-600" href="#">
         UNRAM
        </a>
       </li>
       <li>
        <a class="text-gray-600 hover:text-green-600" href="#">
         FKIP UNRAM
        </a>
       </li>
       <li>
        <a class="text-gray-600 hover:text-green-600" href="#">
         Pendidikan Mipa
        </a>
       </li>
       <li>
        <a class="text-gray-600 hover:text-green-600" href="#">
          Pendidikan Matematika
        </a>
       </li>
      </ul>
     </div>
     <div class="mb-8 md:mb-0">
      <h3 class="text-lg font-bold mb-2">
       Our Services
      </h3>
      <ul>
       <li>
        <a class="text-gray-600 hover:text-green-600" href="#">
         UNRAM
        </a>
       </li>
       <li>
        <a class="text-gray-600 hover:text-green-600" href="#">
         FKIP UNRAM
        </a>
       </li>
       <li>
        <a class="text-gray-600 hover:text-green-600" href="#">
         Pendidikan Mipa
        </a>
       </li>
       <li>
        <a class="text-gray-600 hover:text-green-600" href="#">
          Pendidikan Matematika
        </a>
       </li>
      </ul>
     </div>
     <div>
      <h3 class="text-lg font-bold mb-2">
       DUKUNG PROGRAM INI
      </h3>
      <p class="mb-4">
       Kirim Saran dan Komentar Anda Serta Subscribe
      </p>
      <form class="flex">
       <input class="px-4 py-2 border border-gray-300 rounded-l focus:outline-none" placeholder="Email" type="email"/>
       <button class="bg-green-600 text-white px-4 py-2 rounded-r hover:bg-green-700">
        Subscribe
       </button>
      </form>
     </div>
    </div>
    <div class="mt-8 text-center text-gray-600">
     <p>
      © Copyright Mentor. All Rights Reserved
     </p>
     <p>
      Designed by Pendidikan Matematika
     </p>
     <div class="mt-4">
      <a class="text-green-600 mx-2" href="#">
       <i class="fab fa-facebook-f">
       </i>
      </a>
      <a class="text-green-600 mx-2" href="#">
       <i class="fab fa-twitter">
       </i>
      </a>
      <a class="text-green-600 mx-2" href="#">
       <i class="fab fa-instagram">
       </i>
      </a>
      <a class="text-green-600 mx-2" href="#">
       <i class="fab fa-youtube">
       </i>
      </a>
      <a class="text-green-600 mx-2" href="#">
       <i class="fab fa-linkedin">
       </i>
      </a>
     </div>
    </div>
   </div>
  </footer>
 </body>
</html>
