# evan
portofolio day 1
  <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio | Profesional</title>
    <meta name="description" content="Portofolio online profesional – Lulusan SMK Texmaco Pemalang dengan pengalaman kerja di Indomaret.">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <style>
        :root {
            --primary: #0d6efd;
            --dark: #0b132b;
            --light: #f8f9fa;
            --gray: #6c757d;
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--light);
            color: #212529;
            line-height: 1.6;
            scroll-behavior: smooth;
        }
        header {
            min-height: 100vh;
            background: linear-gradient(120deg, #0d6efd, #003f88);
            color: #fff;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            font-size: 48px;
            font-weight: 700;
        }
        header p {
            margin-top: 15px;
            font-size: 20px;
            opacity: 0.9;
        }
        header a {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 28px;
            background-color: #fff;
            color: var(--primary);
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: 0.3s;
        }
        header a:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: rgba(11,19,43,0.95);
            display: flex;
            justify-content: center;
            z-index: 1000;
        }
        nav a {
            color: #fff;
            padding: 15px 20px;
            text-decoration: none;
            font-weight: 500;
            font-size: 14px;
            transition: 0.3s;
        }
        nav a:hover {
            color: #0d6efd;
        }
        section {
            padding: 80px 20px;
        }
        .container {
            max-width: 1100px;
            margin: auto;
        }
        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }
        .section-title h2 {
            font-size: 32px;
            font-weight: 700;
            color: var(--dark);
        }
        .card {
            background-color: #fff;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            transition: 0.4s;
        }
        .card:hover {
            transform: translateY(-6px);
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }
        ul {
            padding-left: 20px;
        }
        .skills li {
            margin-bottom: 10px;
        }
        footer {
            background-color: var(--dark);
            color: #fff;
            text-align: center;
            padding: 30px 20px;
            font-size: 14px;
        }
        .fade {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease;
        }
        .fade.show {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>

<nav>
    <a href="#home">Home</a>
    <a href="#tentang">Tentang</a>
    <a href="#pendidikan">Pendidikan</a>
    <a href="#pengalaman">Pengalaman</a>
    <a href="#keahlian">Keahlian</a>
    <a href="#kontak">Kontak</a>
</nav>

<header id="home">
    <div>
        <h1>Muhammad Aefany Riyansyah</h1>
        <p>Lulusan SMK Texmaco Pemalang | Jurusan TKJ | Pengalaman Indomaret</p>
        <a href="#kontak">Hubungi Saya</a>
    </div>
</header>

<section id="tentang">
    <div class="container fade">
        <div class="section-title"><h2>Tentang Saya</h2></div>
        <div class="card">
            <p>Saya adalah lulusan SMK Texmaco Pemalang jurusan Teknik Komputer dan Jaringan (TKJ) dengan pengalaman kerja di Indomaret selama 1 tahun. Terbiasa bekerja disiplin, melayani pelanggan dengan baik, serta mampu bekerja secara tim maupun individu. Siap berkembang dan berkontribusi secara profesional.</p>
        </div>
    </div>
</section>

<section id="pendidikan">
    <div class="container fade">
        <div class="section-title"><h2>Pendidikan</h2></div>
        <div class="card">
            <h3>SMK Texmaco Pemalang</h3>
            <p><strong>Jurusan:</strong> Teknik Komputer dan Jaringan (TKJ)</p>
            <p>Dibekali keterampilan teknis dasar komputer dan jaringan, kedisiplinan, serta kesiapan memasuki dunia kerja.</p>
            <p>Dibekali keterampilan kerja, kedisiplinan, dan kesiapan memasuki dunia industri.</p>
        </div>
    </div>
</section>

<section id="pengalaman">
    <div class="container fade">
        <div class="section-title"><h2>Pengalaman Kerja</h2></div>
        <div class="card">
            <h3>Indomaret – Crew Store (1 Tahun)</h3>
            <ul>
                <li>Melayani pelanggan secara ramah dan profesional</li>
                <li>Mengoperasikan mesin kasir dan transaksi harian</li>
                <li>Menata dan mengontrol stok barang</li>
                <li>Menjaga kebersihan dan kerapihan toko</li>
            </ul>
        </div>
    </div>
</section>

<section id="keahlian">
    <div class="container fade">
        <div class="section-title"><h2>Keahlian</h2></div>
        <div class="grid">
            <div class="card">Pelayanan Pelanggan</div>
            <div class="card">Kerja Tim</div>
            <div class="card">Pengoperasian Kasir</div>
            <div class="card">Disiplin & Tanggung Jawab</div>
        </div>
    </div>
</section>

<section id="kontak">
    <div class="container fade">
        <div class="section-title"><h2>Kontak</h2></div>
        <div class="card">
            <p>Email: nama@email.com</p>
            <p>WhatsApp: 08xxxxxxxxxx</p>
            <p>Domisili: Pemalang, Jawa Tengah</p>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2026 Portofolio Online Profesional</p>
</footer>

<script>
    const fades = document.querySelectorAll('.fade');
    const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add('show');
            }
        });
    }, { threshold: 0.2 });
    fades.forEach(fade => observer.observe(fade));
</script>

</body>
</html>
