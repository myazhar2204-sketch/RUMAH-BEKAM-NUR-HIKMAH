# RUMAH-BEKAM-NUR-HIKMAH
Rumah bekam nur hikmah.layanan terapi bekam,pijat full body,totok punggung,totok wajah,gurah
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rumah Bekam Nur Hikmah</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background: #2a9d8f;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://source.unsplash.com/1600x600/?spa,therapy') center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    .hero h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 20px;
      margin-bottom: 20px;
    }
    .btn {
      background: #e76f51;
      color: white;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .service {
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      background: #f9f9f9;
    }
    form {
      max-width: 600px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, textarea, select {
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
    }
    button {
      background: #2a9d8f;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #21867a;
    }
    footer {
      background: #264653;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h2>Rumah Bekam Nur Hikmah</h2>
    <nav>
      <a href="#home">Beranda</a>
      <a href="#layanan">Layanan</a>
      <a href="#tentang">Tentang Kami</a>
      <a href="#pendaftaran">Pendaftaran</a>
      <a href="#kontak">Kontak</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h1>Sehat dengan Terapi Bekam & Refleksi</h1>
    <p>Untuk kesehatan, relaksasi, dan ketenangan jiwa.</p>
    <a href="https://wa.me/6285817412017" class="btn">Booking via WhatsApp</a>
  </section>

  <section id="layanan">
    <h2 style="text-align:center;">Layanan Kami</h2>
    <div class="services">
      <div class="service">
        <h3>Bekam</h3>
        <p>Membantu melancarkan peredaran darah, meredakan pegal, dan menjaga kesehatan tubuh.</p>
      </div>
      <div class="service">
        <h3>Refleksi</h3>
        <p>Pijat refleksi untuk mengurangi stres, memperbaiki metabolisme, dan meningkatkan energi.</p>
      </div>
      <div class="service">
        <h3>Pijat Tradisional</h3>
        <p>Mengurangi ketegangan otot, melancarkan aliran darah, dan memberi rasa rileks.</p>
      </div>
    </div>
  </section>

  <section id="tentang">
    <h2 style="text-align:center;">Tentang Kami</h2>
    <p style="text-align:center; max-width:700px; margin:auto;">
      Rumah Bekam Nur Hikmah berlokasi di Kp. Gerendeng, Desa Jatimulya, Kab. Karawang.
      Kami hadir untuk membantu masyarakat menjaga kesehatan tubuh dengan metode terapi alami seperti bekam, pijat, dan refleksi.
    </p>
  </section>

  <section id="pendaftaran">
    <h2 style="text-align:center;">Formulir Pendaftaran Terapi</h2>
    <form action="https://formspree.io/f/xqakljwy" method="POST">
      <input type="text" name="nama" placeholder="Nama Lengkap" required>
      <input type="tel" name="telepon" placeholder="Nomor Telepon / WhatsApp" required>
      <select name="layanan" required>
        <option value="">Pilih Layanan</option>
        <option value="Bekam">Bekam</option>
        <option value="Refleksi">Refleksi</option>
        <option value="Pijat Tradisional">Pijat Tradisional</option>
      </select>
      <input type="date" name="tanggal" required>
      <textarea name="catatan" rows="4" placeholder="Catatan tambahan (opsional)"></textarea>
      <button type="submit">Daftar Sekarang</button>
    </form>
    <p style="text-align:center; margin-top:10px; font-size:14px; color:#555;">
      *Data Anda aman dan hanya digunakan untuk keperluan pendaftaran terapi.
    </p>
  </section>

  <section id="kontak">
    <h2 style="text-align:center;">Hubungi Kami</h2>
    <p style="text-align:center;">📍 Alamat: Kp. Gerendeng, Desa Jatimulya, Kab. Karawang</p>
    <p style="text-align:center;">📞 Telp/WA: <a href="https://wa.me/6285817412017">0858-1741-2017</a></p>
    <div style="text-align:center; margin-top:20px;">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3962.743..." width="100%" height="300" style="border:0; border-radius:10px;" allowfullscreen="" loading="lazy"></iframe>
    </div>
  </section>

  <footer>
    <p>© 2025 Rumah Bekam Nur Hikmah | Sehat Alami dengan Terapi</p>
  </footer>
</body>
</html>
