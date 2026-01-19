<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Migi Setyo Sugiarto Adi</title>
    <link href="https://fonts.googleapis.com/css2?family=Arial:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --dark: #000000;
            --gray: #333333;
            --light-gray: #f0f0f0;
            --accent: #2c3e50;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #525659;
            color: var(--dark);
            line-height: 1.4;
            padding: 20px;
        }

        /* Tombol Navigasi */
        .controls {
            max-width: 800px;
            margin: 0 auto 20px;
            display: flex;
            justify-content: center;
        }

        .btn-print {
            padding: 10px 25px;
            background: #27ae60;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
            font-size: 14px;
        }

        /* Container Utama CV */
        .cv-paper {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 50px;
            min-height: 297mm;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
        }

        header {
            text-align: left;
            margin-bottom: 25px;
        }

        h1 { font-size: 24px; font-weight: bold; margin-bottom: 5px; }
        .contact-info { font-size: 12px; color: var(--gray); border-bottom: 1px solid #ccc; padding-bottom: 15px; }

        h2 { 
            font-size: 16px; 
            font-weight: bold; 
            margin: 20px 0 10px; 
            border-bottom: 2px solid var(--dark);
            padding-bottom: 2px;
        }

        .content-text { font-size: 12px; text-align: justify; margin-bottom: 15px; }

        .experience-item { margin-bottom: 18px; }
        .item-header { display: flex; justify-content: space-between; font-weight: bold; font-size: 13px; }
        .item-sub { font-style: italic; font-size: 12px; color: #444; margin: 2px 0 5px; }
        .item-desc { font-size: 12px; line-height: 1.5; }

        .skills-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 5px 30px;
        }

        .skill-item { font-size: 12px; }

        /* Responsive Mobile */
        @media (max-width: 600px) {
            .cv-paper { padding: 25px; }
            .item-header { flex-direction: column; }
            .skills-container { grid-template-columns: 1fr; }
            h1 { font-size: 20px; }
        }

        /* Print Settings */
        @media print {
            .controls { display: none; }
            body { background: white; padding: 0; }
            .cv-paper { box-shadow: none; padding: 30px; margin: 0; width: 100%; }
        }
    </style>
</head>
<body>

    <div class="controls">
        <button class="btn-print" onclick="window.print()">🖨️ Cetak ke PDF / Print</button>
    </div>

    <div class="cv-paper">
        <header>
            <h1>MIGI SETYO SUGIARTO ADI</h1>
            <div class="contact-info">
                migisetyosa@gmail.com | 08112683668 | Kota Semarang | Indonesia
            </div>
        </header>

        <section>
            <h2>SUMMARY</h2>
            <p class="content-text">
                Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko. Memiliki latar belakang sebagai Barista, Bartender, Admin Purchasing, hingga Store Manager. Terbukti mampu mengelola inventory, menekan biaya operasional, menjaga standar layanan pelanggan, serta bekerja efektif lintas tim. Terbiasa bekerja dengan SOP, target operasional, dan sistem manajemen berbasis data (Microsoft Excel).
            </p>
        </section>

        <section>
            <h2>OBJECTIVE</h2>
            <p class="content-text">
                Mencari posisi di bidang Food & Beverage Operations / Store Management / Purchasing untuk berkontribusi secara langsung dalam peningkatan efisiensi operasional, kualitas layanan pelanggan, serta pertumbuhan bisnis perusahaan.
            </p>
        </section>

        <section>
            <h2>PROFESSIONAL EXPERIENCE</h2>

            <div class="experience-item">
                <div class="item-header">
                    <span>Bartender</span>
                    <span>Februari 2025 - November 2025</span>
                </div>
                <div class="item-sub">Suji Suan Cai Yu DP Mall Semarang</div>
                <p class="item-desc">Menyiapkan dan menyajikan minuman non-alkohol sesuai SOP perusahaan. Mengelola stok bahan baku dan berhasil mengurangi waste hingga ±15%. Menjaga kebersihan area bar dengan tingkat kepatuhan SOP 100%. Berkontribusi dalam peningkatan kepuasan pelanggan melalui pelayanan cepat dan konsisten.</p>
            </div>

            <div class="experience-item">
                <div class="item-header">
                    <span>Barista</span>
                    <span>September 2024 - Januari 2025</span>
                </div>
                <div class="item-sub">Cotti Coffee Pollux Paragon Semarang</div>
                <p class="item-desc">Menyajikan berbagai minuman kopi dan teh, menjaga kualitas dan kebersihan area kerja, serta memberikan pelayanan pelanggan yang luar biasa. Memahami menu dengan baik, mengelola pesanan dengan efisien, dan menciptakan suasana yang ramah untuk pelanggan. Mengelola stok bahan baku dan melakukan pemeliharaan peralatan.</p>
            </div>

            <div class="experience-item">
                <div class="item-header">
                    <span>Admin Purchasing</span>
                    <span>Juli 2023 - Agustus 2024</span>
                </div>
                <div class="item-sub">TOKO KOPI DJUARA</div>
                <p class="item-desc">Mengelola proses pembelian termasuk pengadaan barang, negosiasi dengan pemasok, serta pengawasan dan pemeliharaan inventaris. Memastikan kelancaran alur komunikasi antara tim internal dan pemasok. Membuat laporan pembelian dan stock menggunakan Microsoft Excel. Membantu efisiensi biaya operasional melalui kontrol pembelian rutin.</p>
            </div>

            <div class="experience-item">
                <div class="item-header">
                    <span>Admin Purchasing</span>
                    <span>Januari 2022 - Agustus 2024</span>
                </div>
                <div class="item-sub">LAIV.IDN</div>
                <p class="item-desc">Bertanggung jawab untuk mengelola proses pengadaan barang, termasuk pemilihan vendor, negosiasi harga, dan penyusunan kontrak. Memastikan kualitas produk dan ketepatan waktu pengiriman serta menyusun laporan pembelian secara berkala untuk analisis anggaran dan perencanaan.</p>
            </div>

            <div class="experience-item">
                <div class="item-header">
                    <span>Store Manager</span>
                    <span>Juni 2021 - Agustus 2024</span>
                </div>
                <div class="item-sub">KOPI REJEKI</div>
                <p class="item-desc">Mengelola operasional harian toko, termasuk pengawasan staf, pengelolaan inventaris, dan pencapaian target penjualan. Menangani keluhan pelanggan dan menjaga kualitas layanan. Memastikan pelayanan yang optimal, serta melaksanakan strategi pemasaran untuk meningkatkan pertumbuhan bisnis dan kepuasan pelanggan.</p>
            </div>

            <div class="experience-item">
                <div class="item-header">
                    <span>Barista</span>
                    <span>Januari 2020 - Juni 2021</span>
                </div>
                <div class="item-sub">KOPI KENANGAN - DP Mall Semarang</div>
                <p class="item-desc">Menyajikan berbagai minuman kopi dan teh berkualitas tinggi, memastikan kepuasan pelanggan melalui pelayanan yang ramah dan efisien. Mengoperasikan mesin espresso, mengelola stok bahan baku, serta menjaga kebersihan dan kerapihan area kerja.</p>
            </div>

            <div class="experience-item" style="margin-bottom: 0;">
                <div class="item-header">
                    <span>Captain Waiters</span>
                    <span>Mei 2015 - Agustus 2017</span>
                </div>
                <div class="item-sub">KOENO KOENI CAFE & GALERY</div>
                <p class="item-desc">Mengelola dan memimpin tim pelayan untuk memastikan pelayanan pelanggan yang berkualitas tinggi. Bertanggung jawab atas penyajian makanan dan minuman, koordinasi pesanan, serta pengaturan ruang makan. Menangani keluhan pelanggan dengan profesionalisme dan menjaga standar kebersihan serta keselamatan.</p>
            </div>
        </section>

        <section>
            <h2>EDUCATION</h2>
            <div class="experience-item">
                <div class="item-header">
                    <span>Tata Boga</span>
                    <span>2012-2015</span>
                </div>
                <div class="item-sub">SMK NEGERI 6 SEMARANG</div>
                <p class="item-desc">Mempelajari teknik dasar dan lanjutan dalam memasak, pengolahan bahan makanan, serta presentasi hidangan. Mencakup praktik langsung dalam persiapan menu, pengembangan resep, dan pengetahuan tentang keamanan pangan.</p>
            </div>
        </section>

        <section>
            <h2>COURSES AND CERTIFICATES</h2>
            <div class="experience-item">
                <div class="item-header" style="font-size: 12px;">
                    <span>Certificate of Competency test for Serving Food and Beverages</span>
                    <span>2015</span>
                </div>
                <div class="item-sub">Collaboration Between State Vocational School 6 Semarang and Crown Plaza Hotel</div>
                <p class="item-desc">Memperoleh pengetahuan mendalam tentang praktik penyajian makanan, layanan pelanggan yang efisien, serta pemahaman tentang standar kebersihan dan keamanan dalam industri makanan dan minuman.</p>
            </div>
        </section>

        <section>
            <h2>SKILLS</h2>
            <div class="skills-container">
                <div class="skill-item">• Cost Control dan Inventory Management</div>
                <div class="skill-item">• Restaurant dan Store Operations</div>
                <div class="skill-item">• Purchasing dan Supplier Coordination</div>
                <div class="skill-item">• Food Safety Management System</div>
                <div class="skill-item">• Handle Complaint</div>
                <div class="skill-item">• Microsoft Excel (Reporting dan Data Management)</div>
                <div class="skill-item">• Warehouse Management System</div>
                <div class="skill-item">• Leadership</div>
                <div class="skill-item">• Teamwork</div>
                <div class="skill-item">• Communication</div>
                <div class="skill-item">• Problem Solving</div>
            </div>
        </section>

        <section>
            <h2>LANGUAGES</h2>
            <div class="skill-item">• Indonesia</div>
        </section>
    </div>

</body>
</html>
