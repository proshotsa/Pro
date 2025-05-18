<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Ibrahim Shot</title>
  <style>
    :root {
      --mint: #0ff;
      --black: #000;
      --white: #fff;
      --gray: #aaa;
    }

    body {
      margin: 0;
      background-color: var(--black);
      color: var(--white);
      font-family: 'Segoe UI', Tahoma, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
      text-align: center;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.3em;
    }

    p {
      color: var(--gray);
      font-size: 1.2em;
      margin: 0.2em 0 1.5em;
    }

    .logo {
      font-size: 2.2em;
      font-weight: bold;
      color: var(--mint);
      margin: 2em 0 1em;
      letter-spacing: 1px;
    }

    .links {
      display: flex;
      flex-direction: column;
      width: 100%;
      max-width: 300px;
      gap: 15px;
      margin-bottom: 2em;
    }

    .links a {
      background-color: var(--white);
      color: var(--black);
      padding: 15px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      transition: background-color 0.3s, color 0.3s;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }

    .links a:hover {
      background-color: var(--mint);
      color: var(--black);
    }

    .social-icons {
      display: flex;
      justify-content: center;
      gap: 25px;
      margin-top: 20px;
    }

    .social-icons a {
      display: inline-block;
    }

    .social-icons img {
      width: 40px;
      height: 40px;
      filter: brightness(0);
      transition: transform 0.3s;
    }

    .social-icons a:hover img {
      transform: scale(1.15);
    }

    footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #666;
    }
  </style>
</head>
<body>

  <h1>Ibrahim Shot</h1>
  <p>حياكم في صفحتي</p>
  <p>للطلب تواصلوا استقرام</p>

  <div class="logo">ProShotSA</div>

  <div class="links">
    <a href="https://www.instagram.com/proshotsa" target="_blank">Instagram</a>
    <a href="https://www.tiktok.com/@proshotsa" target="_blank">TikTok</a>
  </div>

  <div class="social-icons">
    <a href="https://www.tiktok.com/@proshotsa" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/TikTok_icon_black.svg" alt="TikTok">
    </a>
    <a href="https://www.instagram.com/proshotsa" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon_black.svg" alt="Instagram">
    </a>
  </div>

  <footer>
    &copy; 2025 Ibrahim Shot. جميع الحقوق محفوظة.
  </footer>

</body>
</html>
