<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>BroToBro Edits</title>
  <style>
    /* ===== CSS Styles ===== */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f1720;
      color: white;
      text-align: center;
    }
    header {
      background: #ff6b6b;
      padding: 1rem;
      font-size: 1.5rem;
      font-weight: bold;
    }
    h1 { margin-top: 2rem; font-size: 2rem; }
    p { color: #aab3c1; }
    button {
      margin-top: 1rem;
      background: #ff6b6b;
      border: none;
      padding: 10px 20px;
      border-radius: 6px;
      color: white;
      font-size: 1rem;
      cursor: pointer;
    }
    button:hover { background: #ff4040; }
    footer {
      margin-top: 3rem;
      padding: 1rem;
      background: rgba(255,255,255,0.05);
      font-size: 0.9rem;
      color: #aab3c1;
    }
  </style>
</head>
<body>
  <!-- ===== HTML Content ===== -->
  <header>BroToBro Edits</header>

  <main>
    <h1>Hello, I’m BroToBro 👋</h1>
    <p>Creative video editor bringing raw clips to life with smooth transitions & storytelling.</p>
    <button id="btn">Click Me</button>
  </main>

  <footer>
    Contact: 09164955650| 
    <a href="mailto:igwec1174@gmqil.com" style="color:#ff6b6b;">Email Me</a>
  </footer>

  <!-- ===== JavaScript ===== -->
  <script>
    document.getElementById("btn").addEventListener("click", () => {
      alert("Thanks for visiting BroToBro Edits portfolio!");
    });
  </script>
</body>
</html>
