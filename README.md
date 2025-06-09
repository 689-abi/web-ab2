<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Biodata Saya - Abi Lutdfiansyah Said</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .navbar {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #3498db;
      padding: 15px 0;
      z-index: 1000;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }

    .navbar a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
      font-size: 16px;
    }

    .navbar a:hover {
      text-decoration: underline;
    }

    section {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding-top: 80px;
      padding-bottom: 60px;
    }

    .beranda {
      background: linear-gradient(to right, #ffecd2, #fcb69f);
      flex-direction: column;
      text-align: center;
    }

    .beranda h1 {
      font-size: 48px;
      color: #2c3e50;
    }

    .beranda p {
      font-size: 20px;
      color: #34495e;
      max-width: 600px;
      margin: 20px auto;
    }

    .kotak {
      background: white;
      padding: 40px;
      border-radius: 15px;
      box-shadow: 0px 10px 25px rgba(0,0,0,0.1);
      max-width: 900px;
      width: 100%;
    }

    .judul {
      text-align: center;
      margin-bottom: 30px;
    }

    .judul h1 {
      margin: 0;
      color: #2c3e50;
      font-size: 36px;
    }

    .blok {
      margin-bottom: 30px;
    }

    h2 {
      color: #2980b9;
      border-bottom: 2px solid #3498db;
      padding-bottom: 5px;
      margin-bottom: 15px;
    }

    .center {
      text-align: center;
      margin-bottom: 20px;
    }

    .foto-bulat {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 5px solid #3498db;
      object-fit: cover;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      text-align: left;
      padding: 8px 10px;
    }

    th {
      width: 150px;
      color: #2c3e50;
    }

    td a {
      color: #2980b9;
      text-decoration: none;
    }

    td a:hover {
      text-decoration: underline;
    }

    ul {
      padding-left: 20px;
    }

    ul li {
      margin-bottom: 8px;
    }

    .proyek {
      background: linear-gradient(to right, #74ebd5, #acb6e5);
      flex-direction: column;
      text-align: center;
    }

    .proyek h2 {
      font-size: 32px;
      color: #2c3e50;
      margin-bottom: 20px;
    }

    .proyek ul {
      list-style: none;
      padding: 0;
      margin: 0 auto;
      max-width: 700px;
    }

    .proyek li {
      background: white;
      margin: 10px;
      padding: 15px 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: left;
    }

    @media (max-width: 600px) {
      .kotak {
        padding: 20px;
      }

      .foto-bulat {
        width: 120px;
        height: 120px;
      }

      .navbar a {
        margin: 0 10px;
        font-size: 14px;
      }

      .beranda h1 {
        font-size: 32px;
      }
    }
  </style>
</head>
<body>
  <div class="navbar">
    <a href="#beranda">Beranda</a>
    <a href="#biodata">Biodata</a>
    <a href="#proyek">Proyek</a>
  </div>

  <section id="beranda" class="beranda">
    <div>
      <h1>Selamat Datang!</h1>
      <p>Halo, saya <strong>Abi Lutdfiansyah Said</strong>, seorang pelajar yang tertarik pada dunia pengembangan web dan pemrograman. Yuk kenali saya lebih lanjut!</p>
    </div>
  </section>

  <section id="biodata">
    <div class="kotak">
      <div class="judul">
        <h1>BIODATA DIRI</h1>
      </div>

      <div class="blok">
        <h2>Informasi</h2>
        <div class="center">
          <img src="abii.jpg" class="foto-bulat" alt="Foto Profil">
        </div>
        <table>
          <tr><th>Nama</th><th>:</th><td>Abi Lutdfiansyah Said</td></tr>
          <tr><th>Tempat</th><th>:</th><td>Sulang lor</td></tr>
          <tr><th>Tgl. Lahir</th><th>:</th><td>23 April 2009</td></tr>
          <tr><th>Agama</th><th>:</th><td>Islam</td></tr>
          <tr><th>Alamat</th><th>:</th><td>Sulang lor, Patalan, Jetis, Bantul</td></tr>
          <tr><th>Email</th><th>:</th><td>lutdfiansyahsaidabi@gmail.com</td></tr>
          <tr><th>No. HP</th><th>:</th><td>088216040747</td></tr>
          <tr><th>Website</th><th>:</th><td><a href="https://abi121318.github.io/World/" target="_blank">https://abi121318.github.io/World/</a></td></tr>
        </table>
      </div>

      <div class="blok">
        <h2>Pendidikan</h2>
        <ul>
          <li><b>2015 - 2021</b> SD 1 Negeri Patalan</li>
          <li><b>2021 - 2024</b> SMP 3 Negeri Jetis</li>
          <li><b>2024 - 2027</b> SMK 1 Negeri Sanden</li>
        </ul>
      </div>

      <div class="blok">
        <h2>Pengalaman Kerja</h2>
        <ul>
          <li><b>2024 - 2027</b> - <i>Back-End Developer</i> di SMK N 1 Sanden</li>
        </ul>
      </div>

      <div class="blok">
        <h2>Keahlian</h2>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>PHP</li>
          <li>CodeIgniter</li>
          <li>Laravel</li>
          <li>NodeJS</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="proyek" class="proyek">
    <div>
      <h2>Proyek Saya</h2>
      <ul>
        <li><strong>Website Portofolio</strong> - Menampilkan biodata dan keahlian saya dengan HTML dan CSS.</li>
        <li><strong>CRUD Siswa</strong> - Aplikasi CRUD berbasis PHP & MySQL menggunakan CodeIgniter.</li>
        <li><strong>Website Artikel</strong> - Platform sederhana untuk menulis dan mengelola artikel dengan Laravel.</li>
        <li><strong>API Backend</strong> - Membangun RESTful API menggunakan NodeJS dan Express.</li>
      </ul>
    </div>
  </section>
</body>
</html>
