<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Migi Setyo Sugiarto Adi</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
    
    <style>
        :root {
            --primary: #2d3436;
            --secondary: #636e72;
            --accent: #0984e3;
            --bg: #f5f6fa;
            --white: #ffffff;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg);
            color: var(--primary);
            line-height: 1.6;
            padding: 20px;
        }

        /* Tombol Download */
        .no-print {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }

        .btn-download {
            background-color: var(--accent);
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            font-size: 16px;
            transition: 0.3s;
        }

        .btn-download:hover { background-color: #0773c5; }

        /* Container CV */
        .cv-container {
            max-width: 800px;
            margin: 0 auto;
            background: var(--white);
            padding: 40px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.08);
            border-radius: 4px;
        }

        header {
            text-align: center;
            border-bottom: 2px solid var(--bg);
            padding-bottom: 20px;
            margin-bottom: 25px;
        }

        h1 { font-size: 24px; letter-spacing: 1px; color: var(--primary); }
        .contact { font-size: 14px; color: var(--secondary); margin-top: 5px; }

        section { margin-bottom: 25px; }
        
        h2 { 
            font-size: 16px; 
            color: var(--accent);
            border-bottom: 1px solid var(--accent);
            padding-bottom: 5px;
            margin-bottom: 15px;
            text-transform: uppercase;
        }

        .item { margin-bottom: 20px; }
        .item-header { 
            display: flex; 
            justify-content: space-between; 
            font-weight: 700; 
            color: var(--primary);
            flex-wrap: wrap; 
        }
        
        .company-info { 
            font-style: italic; 
            color: var(--secondary); 
            font-size: 13px; 
            margin: 4px 0;
            display: block;
        }

        .desc { font-size: 14px; text-align: justify; color: #444; }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 8px;
            font-size: 13px;
        }

        /* Responsive untuk HP */
        @media (max-width: 600px) {
            body { padding: 10px; }
            .cv-container { padding: 20px; }
            .item-header { flex-direction: column; }
            .skills-grid { grid-template-columns: 1fr; }
            h1 { font-size: 20px; }
        }

        @media print {
            .no-print { display: none; }
            body { padding: 0; background: white; }
            .cv-container { box-shadow: none; padding: 0; width: 100%; }
        }
    </style>
</head>
<body>

    <div class="no-print">
        <button class="btn-download" onclick="downloadCV()">📥 Download PDF</button>
    </div>

    <div class="cv-container" id="cv-content">
        <header>
            <h1>MIGI SETYO SUGIARTO ADI [cite: 1]</h1>
            <div class="contact">
                migisetyosa@gmail.com | 08112683668 | Kota Semarang | Indonesia 
            </div>
        </header>

        <section>
            <h2>SUMMARY</h2>
            <p class="desc">
                Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko. Memiliki latar belakang sebagai Barista, Bartender, Admin Purchasing, hingga Store Manager. Terbukti mampu mengelola inventory, menekan biaya operasional, menjaga standar layanan pelanggan, serta bekerja efektif lintas tim.
            </p>
        </section>

        <section>
            <h2>PROFESSIONAL EXPERIENCE</h2>

            <div class="item">
                <div class="item-header">
                    <span>Bartender</span>
                    <span>Februari 2025 - November 2025</span>
                </div>
                <span class="company-info">Suji Suan Cai Yu DP Mall Semarang</span>
                <p class="desc">Menyiapkan dan menyajikan minuman non-alkohol sesuai SOP perusahaan. Mengelola stok bahan baku dan berhasil mengurangi waste hingga ±15%. Menjaga kebersihan area bar dengan tingkat kepatuhan SOP 100%.</p>
            </div>

            <div class="item">
                <div class="item-header">
                    <span>Barista</span>
                    <span>September 2024 - Januari 2025</span>
                </div>
                <span class="company-info">Cotti Coffe Pollux Paragon Semarang</span>
                <p class="desc">Menyajikan berbagai minuman kopi dan teh, menjaga kualitas dan kebersihan area kerja, serta memberikan pelayanan pelanggan yang luar biasa. Mengelola stok bahan baku dan melakukan pemeliharaan peralatan.</p>
            </div>

            <div class="item">
                <div class="item-header">
                    <span>Admin Purchasing</span>
                    <span>Juli 2023 - Agustus 2024</span>
                </div>
                <span class="company-info">TOKO KOPI DJUARA</span>
                <p class="desc">Mengelola proses pembelian termasuk pengadaan barang, negosiasi dengan pemasok, serta pengawasan dan pemeliharaan inventaris. Membuat laporan pembelian dan stock menggunakan Microsoft Excel.</p>
            </div>

            <div class="item">
                <div class="item-header">
                    <span>Store Manager</span>
                    <span>Juni 2021 - Agustus 2024</span>
                </div>
                <span class="company-info">KOPI REJEKI</span>
                <p class="desc">Mengelola operasional harian toko, termasuk pengawasan staf, pengelolaan inventaris, dan pencapaian target penjualan. Menangani keluhan pelanggan dan menjaga kualitas layanan.</p>
            </div>

            <div class="item">
                <div class="item-header">
                    <span>Barista</span>
                    <span>Januari 2020 - Juni 2021</span>
                </div>
                <span class="company-info">KOPI KENANGAN - DP Mall Semarang</span>
                <p class="desc">Menyajikan berbagai minuman kopi dan teh berkualitas tinggi. Mengoperasikan mesin espresso serta mengelola stok bahan baku.</p>
            </div>

            <div class="item">
                <div class="item-header">
                    <span>Captain Waiters</span>
                    <span>Mei 2015 - Agustus 2017</span>
                </div>
                <span class="company-info">KOENO KOENI CAFE & GALERY</span>
                <p class="desc">Mengelola dan memimpin tim pelayan untuk memastikan pelayanan pelanggan berkualitas tinggi. Bertanggung jawab atas penyajian makanan dan minuman serta koordinasi pesanan.</p>
            </div>
        </section>

        <section>
            <h2>EDUCATION</h2>
            <div class="item">
                <div class="item-header">
                    <span>Tata Boga</span>
                    <span>2012-2015</span>
                </div>
                <span class="company-info">SMK NEGERI 6 SEMARANG</span>
                <p class="desc">Mempelajari teknik dasar dan lanjutan dalam memasak, pengolahan bahan makanan, serta presentasi hidangan.</p>
            </div>
        </section>

        <section>
            <h2>SKILLS</h2>
            <div class="skills-grid">
                <div>• Cost Control & Inventory</div>
                <div>• Store Operations</div>
                <div>• Purchasing & Negotiation</div>
                <div>• Food Safety Management</div>
                <div>• Microsoft Excel</div>
                <div>• Leadership & Teamwork</div>
            </div>
        </section>
    </div>

    <script>
        function downloadCV() {
            const element = document.getElementById('cv-content');
            const opt = {
                margin:       [10, 10, 10, 10],
                filename:     'CV_Migi_Setyo_Sugiarto_Adi.pdf',
                image:        { type: 'jpeg', quality: 0.98 },
                html2canvas:  { scale: 2, useCORS: true },
                jsPDF:        { unit: 'mm', format: 'a4', orientation: 'portrait' }
            };
            html2pdf().set(opt).from(element).save();
        }
    </script>
</body>
</html>
