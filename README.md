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
    }

    body {
      background: #0f172a;
      color: white;
    }

    header {
      padding: 20px;
      text-align: center;
      background: #1e293b;
    }

    header h1 {
      font-size: 28px;
    }

    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }

    h2 {
      margin-bottom: 10px;
      color: #38bdf8;
    }

    .card {
      background: #1e293b;
      padding: 15px;
      margin-top: 10px;
      border-radius: 10px;
    }

    button {
      margin-top: 15px;
      padding: 10px 20px;
      background: #38bdf8;
      border: none;
      color: black;
      cursor: pointer;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1e293b;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
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
    <div class="card">HTML</div>
    <div class="card">CSS</div>
    <div class="card">JavaScript</div>
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
