# website-dini
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Diri - LinkedIn Style</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f2ef;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        .header {
            background: linear-gradient(135deg, #0077b5, #005885);
            color: white;
            padding: 20px;
            text-align: center;
        }
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid white;
            margin-bottom: 10px;
        }
        .name {
            font-size: 28px;
            margin: 0;
        }
        .title {
            font-size: 18px;
            margin: 5px 0;
        }
        .location {
            font-size: 14px;
            margin: 5px 0;
        }
        .section {
            padding: 20px;
            border-bottom: 1px solid #e0e0e0;
        }
        .section h2 {
            color: #0077b5;
            margin-bottom: 10px;
        }
        .experience, .education, .skills {
            margin-bottom: 15px;
        }
        .experience h3, .education h3 {
            margin: 0;
            font-size: 16px;
        }
        .experience p, .education p {
            margin: 5px 0;
            color: #666;
        }
        .skills ul {
            list-style: none;
            padding: 0;
        }
        .skills li {
            display: inline-block;
            background: #e0e0e0;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <img src="https://via.placeholder.com/120" alt="Foto Profil" class="profile-pic">
            <h1 class="name">Dini Eka Rahmawati</h1>
            <p class="title">INSTITUT PERTANIAN BOGOR</p>
            <p class="location">DAK CIAWI</p>
        </div>

        <!-- About Section -->
        <div class="section">
            <h2>Tentang</h2>
            <p>Mahasiswa dari program studi Teknologi Rekayasa Komputer di Institut Pertanian Bogor angkatan 61 yang sedang belajar Pemrograman Web. Diberi tugas untuk membuat Biodata diri.</p>
        </div>

        <!-- Experience Section -->
        <div class="section">
            <h2>Pengalaman</h2>
            <div class="experience">
                <h3>Staff Humas</h3>
                <p><strong>Humas Micro IT</strong> | Bulan Tahun - Bulan Tahun</p>
                <p>Bagian Content </p>
            </div>
            <div class="experience">
                <h3>Jabatan 2</h3>
                <p><strong>Perusahaan 2</strong> | Bulan Tahun - Sekarang</p>
                <p>Deskripsi pengalaman kerja lainnya.</p>
            </div>
            <!-- Tambahkan lebih banyak pengalaman sesuai kebutuhan -->
        </div>

        <!-- Education Section -->
        <div class="section">
            <h2>Pendidikan</h2>
            <div class="education">
                <h3>Nama Universitas</h3>
                <p>Gelar | Tahun Lulus</p>
                <p>Deskripsi singkat tentang pendidikan Anda.</p>
            </div>
            <!-- Tambahkan lebih banyak pendidikan jika ada -->
        </div>

        <!-- Skills Section -->
        <div class="section">
            <h2>Keterampilan</h2>
            <ul class="skills">
                <li>Keterampilan 1</li>
                <li>Keterampilan 2</li>
                <li>Keterampilan 3</li>
                <li>Keterampilan 4</li>
                <!-- Tambahkan lebih banyak keterampilan -->
            </ul>
        </div>

        <!-- Footer or Additional Sections -->
        <div class="section">
            <h2>Kontak</h2>
            <p>Email: email@anda.com</p>
            <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
            <!-- Tambahkan bagian lain seperti proyek, sertifikasi, dll. -->
        </div>
    </div>
</body>
</html>
