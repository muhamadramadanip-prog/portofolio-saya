[index.html](https://github.com/user-attachments/files/27276189/index.html)[Uploading index<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio | Muhamad Ramadani Putra</title>
    <style>
        /* Gaya Dasar */
        * { box-sizing: border-box; }
        body { font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; margin: 0; line-height: 1.6; color: #333; background: #f4f4f7; scroll-behavior: smooth; }
        
        header { background: #2c3e50; color: #fff; padding: 1rem 0; position: fixed; width: 100%; top: 0; z-index: 1000; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        
        /* Kontainer */
        .container { width: 85%; max-width: 1100px; margin: auto; overflow: hidden; padding: 80px 20px; }
        
        /* Hero Section */
        #hero { height: 70vh; display: flex; flex-direction: column; justify-content: center; align-items: center; background: linear-gradient(rgba(44, 62, 80, 0.8), rgba(44, 62, 80, 0.8)), url('https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&auto=format&fit=crop&w=1352&q=80'); background-size: cover; background-position: center; color: white; text-align: center; padding: 20px; }
        #hero h1 { font-size: 3rem; margin-bottom: 10px; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
        #hero p { font-size: 1.2rem; margin-bottom: 20px; }

        /* Project Cards */
        .project-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; margin-top: 30px; }
        .card { background: white; padding: 25px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); transition: transform 0.3s ease; border-top: 5px solid #e67e22; }
        .card:hover { transform: translateY(-10px); }
        .card h3 { color: #2c3e50; margin-top: 0; }

        /* Section Title */
        h2 { text-align: center; color: #2c3e50; margin-bottom: 40px; position: relative; }
        h2::after { content: ''; background: #e67e22; height: 3px; width: 50px; position: absolute; bottom: -10px; left: 50%; transform: translateX(-50%); }

        /* Footer */
        footer { background: #2c3e50; color: white; text-align: center; padding: 30px 0; margin-top: 50px; }
        
        /* Tombol */
        .btn { display: inline-block; background: #e67e22; color: white; padding: 12px 30px; text-decoration: none; border-radius: 30px; font-weight: bold; transition: 0.3s; box-shadow: 0 4px 6px rgba(0,0,0,0.1); }
        .btn:hover { background: #d35400; transform: scale(1.05); }

        /* Link Styling */
        a { color: #e67e22; text-decoration: none; }
        a:hover { text-decoration: underline; }
    </style>
</head>
<body>

    <header>
        <strong>Muhamad Ramadani Putra</strong>
    </header>

    <section id="hero">
        <h1>Halo, Saya Muhamad Ramadani Putra</h1>
        <p>Web Developer | Designer | Engineering</p>
        <a href="https://wa.me/6283892871730" class="btn" target="_blank">Hubungi via WhatsApp</a>
    </section>

    <div class="container">
        <section id="tentang">
            <h2>Tentang Saya</h2>
            <p style="text-align: center; max-width: 800px; margin: auto;">
                Saya adalah seorang pengembang web yang bersemangat untuk menciptakan solusi digital yang kreatif dan fungsional. 
                Selain memiliki minat besar di dunia teknisi, saya juga aktif dalam berorganisasi. 
                Pengalaman kepemimpinan saya meliputi jabatan sebagai <strong>Ketua OSIS</strong> dan <strong>Sekretaris 2 OSIS</strong>, 
                yang membentuk karakter saya menjadi pribadi yang disiplin dan bertanggung jawab.
            </p>
        </section>

        <section id="proyek">
            <h2>Proyek Saya</h2>
            <div class="project-grid">
                <div class="card">
                    <h3>Personal Portfolio</h3>
                    <p>Website portofolio interaktif yang dibangun menggunakan HTML5 dan CSS3 melalui Visual Studio Code.</p>
                </div>
                <div class="card">
                    <h3>Organization Portal</h3>
                    <p>Konsep aplikasi web untuk manajemen administrasi organisasi sekolah agar lebih efisien.</p>
                </div>
                <div class="card">
                    <h3>Engineering Blog</h3>
                    <p>Eksperimen desain blog teknis yang membahas seputar dunia engineering dan teknologi terbaru.</p>
                </div>
            </div>
        </section>

        <section id="kontak" style="text-align: center;">
            <h2>Kontak</h2>
            <p>📧 Email: <a href="mailto:muhamadramadanip@gmail.com">muhamadramadanip@gmail.com</a></p>
            <p>📱 Lokasi: Indonesia</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Muhamad Ramadani Putra. Dibuat dengan penuh semangat.</p>
    </footer>

</body>
</html>.html…]()
