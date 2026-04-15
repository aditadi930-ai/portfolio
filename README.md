<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio Saya</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
      scroll-behavior: smooth;
    }

    body {
      background: #0f172a;
      color: white;
    }

    header {
      padding: 40px 20px;
      text-align: center;
      background: #1e293b;
      animation: fadeDown 1s ease;
    }

    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #38bdf8;
      margin-bottom: 15px;
      animation: fadeIn 1.5s ease;
    }

    header h1 {
      font-size: 26px;
    }

    header p {
      color: #94a3b8;
    }

    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
      opacity: 0;
      transform: translateY(30px);
      animation: fadeUp 1s ease forwards;
    }

    section:nth-child(2) { animation-delay: 0.3s; }
    section:nth-child(3) { animation-delay: 0.6s; }
    section:nth-child(4) { animation-delay: 0.9s; }
    section:nth-child(5) { animation-delay: 1.2s; }

    h2 {
      margin-bottom: 10px;
      color: #38bdf8;
    }

    .card {
      background: #1e293b;
      padding: 15px;
      margin-top: 10px;
      border-radius: 10px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      background: #334155;
    }

    button {
      margin-top: 15px;
      padding: 10px 20px;
      background: #38bdf8;
      border: none;
      color: black;
      cursor: pointer;
      border-radius: 5px;
      transition: 0.3s;
    }

    button:hover {
      background: #0ea5e9;
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1e293b;
      margin-top: 30px;
      animation: fadeUp 1s ease;
    }

    /* ANIMATIONS */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes fadeDown {
      from {
        opacity: 0;
        transform: translateY(-30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="profile.jpg" alt="Foto Profile" class="profile-img">
    <h1>Halo, Saya [Nama Kamu]</h1>
    <p>Calon Web Developer 🚀</p>
  </header>

  <section>
    <h2>Tentang Saya</h2>
    <div class="card">
      <p>Saya sedang belajar membuat website menggunakan HTML, CSS, dan JavaScript.</p>
    </div>
  </section>

  <section>
    <h2>Skill</h2>
    <div class="card">AutoCAD</div>
    <div class="card">SketchUp</div>
    <div class="card">Enscape (3D Rendering)</div>
  </section>

  <section>
    <h2>Project</h2>
    <div class="card">Website Pertama Saya</div>
    <div class="card">Coming Soon...</div>
  </section>

  <section>
    <h2>Kontak</h2>
    <div class="card">
      <p>Email: emailkamu@gmail.com</p>
      <button onclick="hubungi()">Hubungi Saya</button>
    </div>
  </section>

  <footer>
    <p>© 2026 Portfolio Saya</p>
  </footer>

  <script>
    function hubungi() {
      alert("Terima kasih sudah menghubungi saya!");
    }
  </script>

</body>
</html>
