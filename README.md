<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ZYNEX — Build the Future</title>

  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body {
      min-height:100vh;
      background: radial-gradient(circle at top, #0f172a, #020617);
      color:white;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      overflow:hidden;
      padding:20px;
      position:relative;
    }

    /* Particles */
    .particle {
      position:absolute;
      width:4px;
      height:4px;
      background:#1E90FF;
      border-radius:50%;
      animation: float 8s linear infinite;
      opacity:0.7;
    }

    @keyframes float {
      0% { transform: translateY(0px) translateX(0px); opacity:0.3; }
      50% { transform: translateY(-200px) translateX(50px); opacity:0.8; }
      100% { transform: translateY(0px) translateX(-30px); opacity:0.3; }
    }

    .container {
      max-width:500px;
      width:100%;
      z-index:1;
      position:relative;
    }

    .logo {
      font-size:3rem;
      font-weight:800;
      letter-spacing:4px;
      animation: fadeIn 1s ease forwards;
    }

    .logo span {
      color:#1E90FF;
      text-shadow:0 0 20px rgba(30,144,255,0.8);
    }

    .tagline {
      margin-top:15px;
      font-size:1.2rem;
      color:#cbd5f5;
      opacity:0;
      animation: fadeIn 1s ease forwards 0.5s;
    }

    .coming {
      margin:30px 0;
      font-size:1.4rem;
      font-weight:600;
      color:#00E5FF;
      text-shadow:0 0 10px rgba(0,229,255,0.6);
      opacity:0;
      animation: fadeIn 1s ease forwards 1s;
    }

    .divider {
      width:80px;
      height:4px;
      background:#1E90FF;
      margin:20px auto;
      border-radius:10px;
      opacity:0;
      animation: fadeIn 1s ease forwards 0.8s;
    }

    .contact {
      font-size:1rem;
      color:#94a3b8;
      opacity:0;
      animation: fadeIn 1s ease forwards 1.5s;
    }

    .contact a {
      color:#1E90FF;
      text-decoration:none;
      font-weight:500;
    }

    .contact a:hover { text-decoration:underline; }

    footer {
      margin-top:40px;
      font-size:0.8rem;
      color:#64748b;
      opacity:0;
      animation: fadeIn 1s ease forwards 1.8s;
    }

    @keyframes fadeIn {
      to { opacity:1; }
    }
  </style>
</head>

<body>
  <!-- Particles -->
  <div class="particle" style="top:80%; left:20%; animation-duration:10s;"></div>
  <div class="particle" style="top:60%; left:70%; animation-duration:12s;"></div>
  <div class="particle" style="top:30%; left:50%; animation-duration:8s;"></div>
  <div class="particle" style="top:10%; left:30%; animation-duration:15s;"></div>
  <div class="particle" style="top:40%; left:80%; animation-duration:9s;"></div>

  <div class="container">
    <div class="logo">ZYNE<span>X</span></div>
    <div class="tagline">Build the Future</div>
    <div class="divider"></div>
    <div class="coming">🚀 Coming Soon</div>
    <div class="contact">
      Contact us at <br />
      <a href="mailto:zynex.future@gmail.com">zynex.future@gmail.com</a>
    </div>
    <footer>© 2026 ZYNEX. All rights reserved.</footer>
  </div>
</body>
</html>

<!--
**utkarxx/Utkarxx** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
