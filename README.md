<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Мои ссылки</title>
  <style>
    :root {
      --bg: #5e5e5e; /* темно-серый оттенок дерева */
      --accent: #003366; /* глубокий синий цвет */
      --text: #f1f1f1;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Inter, system-ui, Segoe UI, Roboto, "Helvetica Neue", Arial;
      background: 
        linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
        url("https://www.toptal.com/designers/subtlepatterns/uploads/wood_pattern.png"); /* текстура дерева */
      background-size: cover;
      background-position: center;
      color: var(--text);
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 24px;
    }

    .card {
      width: 100%;
      max-width: 520px;
      background: rgba(0, 0, 0, 0.65);
      border-radius: 16px;
      padding: 28px;
      text-align: center;
      box-shadow: 0 8px 40px rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(4px);
    }

    .avatar {
      width: 110px;
      height: 110px;
      border-radius: 50%;
      object-fit: cover;
      margin: 0 auto 16px;
      display: block;
      border: 3px solid rgba(255,255,255,0.2);
    }

    h1 { margin: 0 0 6px; font-size: 20px; }
    p.desc { margin: 0 0 18px; color: rgba(255,255,255,0.8); }

    .links {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 12px 16px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: 600;
      background: linear-gradient(135deg, #0b0b22, #1a1a3d);
      border: 1px solid rgba(255,255,255,0.1);
      color: var(--text);
      transition: all 0.3s ease;
    }

    .btn:hover {
      background: linear-gradient(135deg, var(--accent), #001a33);
      box-shadow: 0 0 20px rgba(0, 51, 102, 0.7);
      transform: scale(1.03);
    }

    .btn:active {
      transform: scale(0.97);
      box-shadow: 0 0 10px rgba(0, 51, 102, 0.8) inset;
    }

    .btn .icon {
      width: 20px;
      height: 20px;
      display: inline-block;
    }

    .socials {
      margin-top: 14px;
      display: flex;
      gap: 12px;
      justify-content: center;
    }

    .socials a {
      opacity: 0.9;
      text-decoration: none;
      color: var(--text);
      font-size: 18px;
      transition: 0.3s;
    }

    .socials a:hover {
      color: var(--accent);
    }

    @media (max-width:420px) {
      .card { padding: 20px; }
    }
  </style>
</head>
<body>
  <div class="card">
    <img class="avatar" src="D:\asia\фышф.jpg" alt="Аватар">
    <h1>Твоё имя</h1>
    <p class="desc">"121212121"</p>

    <div class="links">
      <a class="btn" href="https://t.me/asia_decor_urg" target="_blank" rel="noopener">
        <span class="icon">📩</span>Telegram
      </a>
      <a class="btn" href="https://www.instagram.com/asia_decor_urgench/" target="_blank" rel="noopener">
        <span class="icon">📸</span>Instagram
      </a>
      <a class="btn" href="https://vk.com/your" target="_blank" rel="noopener">
        <span class="icon">👥</span>OLX
      </a>
      <a class="btn" href="https://youtube.com/@your" target="_blank" rel="noopener">
        <span class="icon">▶️</span>YouTube
      </a>
    </div>

    <div class="socials">
      <a href="asiadecor@gmail.com" title="Email">✉️</a>
      <a href="https://wa.me/123456789" title="WhatsApp">💬</a>
      <a href="https://github.com/your" title="GitHub">🐙</a>
    </div>
  </div>
</body>
</html>
