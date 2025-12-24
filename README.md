
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Merry Christmas ❤️</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #8b0000, #ff4d4d);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      overflow: hidden;
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      border-radius: 20px;
      padding: 40px 50px;
      text-align: center;
      box-shadow: 0 0 30px rgba(0,0,0,0.3);
      backdrop-filter: blur(8px);
      max-width: 420px;
    }

    h1 {
      font-size: 38px;
      margin-bottom: 10px;
      color: #fff;
    }

    h2 {
      font-size: 22px;
      font-weight: normal;
      margin-bottom: 25px;
      color: #ffe6e6;
    }

    p {
      font-size: 18px;
      line-height: 1.6;
    }

    .heart {
      font-size: 40px;
      animation: pulse 1.5s infinite;
      margin: 15px 0;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }

    .tree {
      font-size: 50px;
      margin-top: 20px;
    }

    .snow {
      position: absolute;
      top: -10px;
      color: white;
      animation: fall linear infinite;
      opacity: 0.8;
    }

    @keyframes fall {
      to {
        transform: translateY(110vh);
      }
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>🎄 Merry Christmas 🎄</h1>
    <h2>My Bachha ❤️</h2>

    <div class="heart">💖</div>

    <p>
      This Christmas feels warmer,<br>
      sweeter, and more beautiful<br>
      because of <b>you</b>.<br><br>
      May every smile of yours shine<br>
      brighter than Christmas lights,<br>
      and may my heart always find<br>
      its way to yours.
    </p>

    <div class="tree">🎄✨🎁</div>
  </div>

  <!-- Snowflakes -->
  <script>
    for (let i = 0; i < 40; i++) {
      const snow = document.createElement("div");
      snow.className = "snow";
      snow.innerHTML = "❄";
      snow.style.left = Math.random() * 100 + "vw";
      snow.style.animationDuration = (3 + Math.random() * 5) + "s";
      snow.style.fontSize = (10 + Math.random() * 20) + "px";
      document.body.appendChild(snow);
    }
  </script>

</body>
</html>
