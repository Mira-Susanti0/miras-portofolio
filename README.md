<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Mira Susanti</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color:black;
            background-color: greenyellow;
        }
        header {
            background-color:beige;
            color:green;
            padding: 1em 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        section {
            padding: 2em 0;
        }
        h2 {
            color:black;
        }
        .project, .experience, .education {
            margin-bottom: 1.5em;
            background: #fff;
            padding: 1em;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .project img {
            max-width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        .contact-form {
            max-width: 600px;
            margin: auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.8em;
            margin: 0.5em 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #333333;
            color: #fff;
            border: none;
            padding: 0.8em;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Portofolio Mira Susanti</h1>
            <p>Pengembang Perangkat Lunak dan Gim</p>
        </div>
    </header>

    <div class="container">
        <section id="about">
            <h2>Tentang Saya</h2>
            <p>Halo! Saya Mira Susanti, seorang pengembang perangkat lunak dan gim dengan pengalaman dalam berbagai teknologi. Saya bersemangat untuk menciptakan solusi teknologi inovatif dan menyelesaikan tantangan pengembangan yang kompleks.</p>
        </section>

        <section id="projects">
            <h2>Proyek-Proyek</h2>
            <div class="project">
                <h3>Proyek 1: Sistem Manajemen Inventaris</h3>
                <p><strong>Deskripsi:</strong> Aplikasi web untuk manajemen inventaris menggunakan React dan Node.js. Memungkinkan pengguna untuk menambah, menghapus, dan memodifikasi item inventaris secara real-time.</p>
                <p><strong>Teknologi:</strong> React, Node.js, MongoDB</p>
            </div>

            <div class="project">
                <h3>Proyek 2: Gim 2D Platformer</h3>
                <p><strong>Deskripsi:</strong> Gim platformer 2D yang dikembangkan menggunakan Unity. Fitur termasuk level yang dapat dimainkan dan mekanika fisika sederhana.</p>
                <p><strong>Teknologi:</strong> Unity, C#</p>
            </div>
        </section>

        <section id="skills">
            <h2>Keahlian Teknis</h2>
            <ul>
                <li>Bahasa Pemrograman: JavaScript, Python, C#</li>
                <li>Framework dan Teknologi: React, Node.js, Unity</li>
                <li>Alat dan Platform: Git, Docker, AWS</li>
            </ul>
        </section>

        <section id="experience">
            <h2>Pengalaman Kerja</h2>
            <div class="experience">
                <h3>Pengembang Perangkat Lunak - PT Teknologi Canggih</h3>
                <p><strong>Periode:</strong> Januari 2021 - Sekarang</p>
                <p><strong>Deskripsi Pekerjaan:</strong> Mengembangkan aplikasi web dan API menggunakan Node.js dan React. Bekerja sama dengan tim untuk merancang solusi yang scalable dan performa tinggi.</p>
            </div>
        </section>

        <section id="education">
            <h2>Pendidikan</h2>
            <div class="education">
                <h3>Gelar Sarjana dalam Ilmu Komputer - Universitas Teknologi</h3>
                <p><strong>Tanggal Lulus:</strong> Mei 2020</p>
            </div>
        </section>

        <section id="blog">
            <h2>Blog dan Artikel</h2>
            <ul>
                <li><a href="https://blog.mirasusanti.com/article1" target="_blank">Artikel 1: Memulai dengan React</a></li>
                <li><a href="https://blog.mirasusanti.com/article2" target="_blank">Artikel 2: Panduan Lengkap Pengembangan Gim dengan Unity</a></li>
            </ul>
        </section>

        <section id="contact">
            <h2>Kontak</h2>
            <div class="contact-form">
                <form action="mailto:mira.susanti@example.com" method="post" enctype="text/plain">
                    <input type="text" name="name" placeholder="Mira Susanti" required>
                    <input type="email" name="email" placeholder="sancans2107@gmail.com" required>
                    <textarea name="message" rows="4" placeholder="Tidak Perlu Kata Kata Yang Penting Bukti Nyata" required></textarea>
                    <button type="submit">Kirim Pesan</button>
                </form>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Mira Susanti. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
