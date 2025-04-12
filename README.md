<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>RG_Maro | روابط التواصل</title>
  <style>
    body {
      background: #111;
      color: #fff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 50px 20px;
    }
    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      background: url('https://via.placeholder.com/120') center/cover;
      margin-bottom: 20px;
    }
    h1 {
      margin-bottom: 10px;
      font-size: 2em;
    }
    .link {
      display: block;
      width: 100%;
      max-width: 300px;
      background: #1e1e1e;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin: 10px 0;
      border-radius: 8px;
      text-decoration: none;
      transition: background 0.3s;
    }
    .link:hover {
      background: #333;
    }
  </style>
</head>
<body>
  <div class="profile-pic"></div>
  <h1>RG_Maro</h1>
  <a class="link" href="https://www.instagram.com/rg__maro?igsh=MWkwY3RkbHJraWtpYQ==" target="_blank">📸 Instagram</a>
  <a class="link" href="https://youtube.com/@rg_maro?si=bK2uJ4tHoD73Pwws" target="_blank">▶️ YouTube</a>
  <a class="link" href="https://tiktok.com/@rg_maro.0" target="_blank">🎵 TikTok</a>
  <a class="link" href="https://discord.gg/funksKWwwY" target="_blank">💬 Discord Server</a>
</body>
</html>
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>موقعي مع نغمة</title>
</head>
<body>
  <h1>مرحبًا بك!</h1>

  <audio id="bg-sound" src="music.mp3" preload="auto"></audio>

  <script>
    window.addEventListener("click", function() {
      const audio = document.getElementById("bg-sound");
      audio.play();
    }, { once: true });

    alert("اضغط في أي مكان لتشغيل الصوت 🎵");
  </script>
</body>
</html>
