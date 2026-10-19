<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio - David John</title>
    <style>
        /* CSS Reset & Variable */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-color: #f8fafc;
            --text-muted: #94a3b8;
            --primary-color: #38bdf8;
            --accent-color: #0284c7;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            padding-bottom: 50px;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 8%;
            background-color: rgba(15, 23, 42, 0.9);
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid #334155;
        }

        .logo {
            font-size: 1.2rem;
            font-weight: bold;
            color: var(--primary-color);
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            color: var(--text-color);
            text-decoration: none;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--primary-color);
        }

        .btn-hire {
            background-color: var(--primary-color);
            color: #0f172a;
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: bold;
            text-decoration: none;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 80px 20px 40px;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .hero p {
            color: var(--text-muted);
            max-width: 600px;
            margin: 0 auto 20px;
        }

        /* Main Container */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
        }

        section {
            margin-bottom: 60px;
        }

        h2.section-title {
            font-size: 1.8rem;
            color: var(--primary-color);
            border-bottom: 2px solid #334155;
            padding-bottom: 8px;
            margin-bottom: 24px;
        }

        /* Card Styles */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: var(--card-bg);
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #334155;
        }

        .card h3 {
            margin-bottom: 8px;
            color: #fff;
        }

        .card .subtitle {
            color: var(--primary-color);
            font-size: 0.9rem;
            margin-bottom: 10px;
        }

        .card p, .card ul {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        .card ul {
            padding-left: 20px;
        }

        /* Tags / Badges */
        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 10px;
        }

        .tag {
            background-color: #334155;
            color: var(--primary-color);
            padding: 5px 12px;
            border-radius: 15px;
            font-size: 0.85rem;
        }

        /* Contact Section */
        .contact-box {
            background-color: var(--card-bg);
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            border: 1px solid #334155;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
            flex-wrap: wrap;
        }

        .contact-item {
            color: var(--primary-color);
            text-decoration: none;
            background: #334155;
            padding: 10px 20px;
            border-radius: 8px;
        }

        .contact-item:hover {
            background: var(--accent-color);
            color: #fff;
        }

        footer {
            text-align: center;
            color: var(--text-muted);
            font-size: 0.85rem;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <!-- Header / Navbar -->
    <nav>
        <div class="logo">DAVID JOHN</div>
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#capabilities">What I Can Do</a></li>
            <li><a href="#achievement">Achievement</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <a href="#contact" class="btn-hire">Hire Me</a>
    </nav>

    <!-- Hero Section -->
    <div class="hero">
        <h1>David John</h1>
        <p>Mahasiswa S1 Sistem Informasi - Universitas Negeri Surabaya</p>
        <p>Minat kuat dalam Fotografi, Video Editing, dan Pengembangan Konten Kreatif serta Pemrograman.</p>
    </div>

    <div class="container">
        
        <!-- About Me Section -->
        <section id="about">
            <h2 class="section-title">About Me</h2>
            <div class="card" style="margin-bottom: 20px;">
                <p>Mahasiswa program studi Sistem Informasi di Universitas Negeri Surabaya dengan minat kuat pada bidang fotografi, video editing, dan pengembangan konten kreatif. Memiliki pengalaman aktif dalam bidang operasional multimedia, dokumentasi acara, serta pengelolaan program kegiatan.</p>
            </div>

            <h3>Pendidikan</h3>
            <div class="grid" style="margin-top: 15px; margin-bottom: 25px;">
                <div class="card">
                    <h3>S1 Sistem Informasi</h3>
                    <div class="subtitle">Universitas Negeri Surabaya (2026 - Sekarang)</div>
                </div>
                <div class="card">
                    <h3>SMA IPA</h3>
                    <div class="subtitle">SMAS Kalam Kudus Medan (2023 - 2026)</div>
                </div>
            </div>

            <h3>Pengalaman & Aktivitas Saat Ini</h3>
            <div class="grid" style="margin-top: 15px;">
                <div class="card">
                    <h3>Event Program Coordinator</h3>
                    <div class="subtitle">Ibadah Perayaan Natal (Desember 2026)</div>
                    <p>Menyusun susunan acara dan mengoordinasikan alur jalannya seluruh program ibadah perayaan.</p>
                </div>
                <div class="card">
                    <h3>Tim Multimedia & Praise Worship</h3>
                    <div class="subtitle">Retreat Mahasiswa Poltekkes Gizi (Maret 2026)</div>
                    <p>Bertanggung jawab atas kelancaran operasional multimedia serta mengiringi musik ibadah (Cajonist).</p>
                </div>
                <div class="card">
                    <h3>Videographer & Photographer</h3>
                    <div class="subtitle">Retreat Generasi Anak Panah (Januari 2026)</div>
                    <p>Mengambil dan memproduksi dokumentasi berupa foto serta video kegiatan seluruh peserta.</p>
                </div>
            </div>
        </section>

        <!-- What I Can Do Section -->
        <section id="capabilities">
            <h2 class="section-title">What I Can Do</h2>
            <div class="grid">
                <div class="card">
                    <h3>Software & Tools</h3>
                    <div class="tags">
                        <span class="tag">CapCut</span>
                        <span class="tag">Canva</span>
                        <span class="tag">Google Workspace</span>
                        <span class="tag">HTML/CSS</span>
                    </div>
                </div>
                <div class="card">
                    <h3>Soft Skills</h3>
                    <div class="tags">
                        <span class="tag">Public Speaking</span>
                        <span class="tag">Creative Thinking</span>
                        <span class="tag">Teamwork</span>
                        <span class="tag">Event Management</span>
                    </div>
                </div>
                <div class="card">
                    <h3>Bahasa</h3>
                    <div class="tags">
                        <span class="tag">Bahasa Indonesia (Aktif)</span>
                        <span class="tag">Bahasa Inggris</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Achievement Section -->
        <section id="achievement">
            <h2 class="section-title">Achievement & Certification</h2>
            <div class="grid">
                <div class="card">
                    <h3>Siswa Tersertifikasi Gemini</h3>
                    <div class="subtitle">Google for Education (Oktober 2026)</div>
                    <p>Sertifikasi kemampuan penggunaan Al Gemini untuk efisiensi dan alur kerja digital.</p>
                </div>
                <div class="card">
                    <h3>Financial Literacy and Soft Skill</h3>
                    <div class="subtitle">DBS Foundation & Plan Indonesia (Agustus 2026)</div>
                    <p>Peserta pelatihan literasi keuangan dan pengembangan soft skill profesional.</p>
                </div>
                <div class="card">
                    <h3>Juara 3 Lomba Vokal Grup</h3>
                    <div class="subtitle">Imlek Fair Kalam Kudus Medan (Februari 2024)</div>
                    <p>Meraih posisi juara 3 sebagai Drummer dalam kompetisi vokal grup.</p>
                </div>
                <div class="card">
                    <h3>Juara 3 Lomba Paduan Suara</h3>
                    <div class="subtitle">Santa's Magical Village (Desember 2023)</div>
                    <p>Meraih Juara 3 Paduan Suara Tingkat SMA sebagai penanyi Tenor.</p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2 class="section-title">Contact</h2>
            <div class="contact-box">
                <h3>Mari Bekerja Sama!</h3>
                <p>Terbuka untuk peluang proyek multimedia, dokumentasi, maupun pengembangan web.</p>
                <div class="contact-links">
                    <a href="mailto:davidjohnang@gmail.com" class="contact-item">Email: davidjohnang@gmail.com</a>
                    <a href="https://linkedin.com/in/david-john-369380441" target="_blank" class="contact-item">LinkedIn Profile</a>
                    <a href="tel:081362730922" class="contact-item">WhatsApp / Telp</a>
                </div>
            </div>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 David John. All rights reserved.</p>
    </footer>

</body>
</html>
