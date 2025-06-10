<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>우리 결혼합니다</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * { margin:0; padding:0; box-sizing:border-box; }
    html, body { height:100%; font-family:'Montserrat', sans-serif; background:#fafafa; color:#333; }
    a { text-decoration:none; color:inherit; }

    /* Hero Section */
    .hero {
      position:relative;
      width:100%; height:80vh;
      background:url('hero.jpg') center/cover no-repeat;
      display:flex; flex-direction:column; align-items:center; justify-content:center; text-align:center;
    }
    .hero::after {
      content:''; position:absolute; inset:0; background:rgba(0,0,0,0.4);
    }
    .hero-content {
      position:relative; z-index:1; color:#fff;
    }
    .hero h1 {
      font-family:'Playfair Display', serif;
      font-size:3em; margin-bottom:0.5em;
    }
    .hero p {
      font-size:1.2em; margin-bottom:1.5em;
    }
    .scroll-down {
      position:absolute; bottom:20px; font-size:1.5em; color:#fff;
      animation: bounce 2s infinite;
    }
    @keyframes bounce {
      0%,100% { transform:translateY(0); }
      50% { transform:translateY(10px); }
    }

    /* Content Container */
    .content {
      max-width:640px; margin:auto; padding:0 20px 40px;
      transform:translateY(-60px);
    }

    /* Photo Section */
    .photo {
      text-align:center; margin-bottom:30px;
    }
    .photo img {
      width:100%; max-width:400px; border-radius:16px;
      box-shadow:0 4px 12px rgba(0,0,0,0.1);
    }

    /* Invitation Text */
    .section {
      margin-bottom:40px; text-align:center;
    }
    .section h2 {
      font-family:'Playfair Display', serif;
      font-size:2em; margin-bottom:0.5em;
    }
    .section p {
      font-size:1em; line-height:1.6; color:#555;
    }

    /* Buttons */
    .buttons {
      display:flex; justify-content:center; gap:20px; margin-top:20px;
    }
    .btn {
      padding:12px 24px; background:#333; color:#fff;
      border-radius:30px; font-weight:600; transition:background 0.3s;
    }
    .btn:hover { background:#555; }

    /* Footer */
    .footer {
      text-align:center; font-size:0.9em; color:#aaa; padding:40px 0;
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <div class="hero">
    <div class="hero-content">
      <h1> 수빈 💛 예림 </h1>
      <p>2025년 09월 13일 토요일 오후 4시<br>경기도 수원시 더아리엘</p>
    </div>
    <div class="scroll-down">⌄</div>
  </div>

  <!-- Main Content -->
  <div class="content">
    <!-- Couple Photo -->
    <div class="photo">
      <img src="couple.jpg" alt="수빈과 예림">
    </div>

    <!-- Invitation Message -->
    <div class="section">
      <h2>Invitation</h2>
      <p>선선한 바람에 마음이 물드는 9월,<br>두 사람이 함께 걸어온 시간의 결실을 맺고<br>이제 믿음 안에서 하나 되어<br>새로운 가정을 이루려 합니다.<br><br>서로를 향한 사랑과 신뢰를 바탕으로<br>하나님 안에서 시작하는 이 걸음이<br>더 깊고 단단해질 수 있도록<br>함께 축복해주시고 따뜻한 응원으로<br>격려해주시면 감사하겠습니다.</p>
    </div>

    <!-- Details -->
    <div class="section">
      <h2>Details</h2>
      <p>📅 2025년 09월 13일 토요일<br>🕓 오후 4시</p>
      <p>📍 경기도 수원시 더아리엘 5층</p>
    </div>

    <!-- Contact & Gift -->
    <div class="section">
      <h2>Contact & Gift</h2>
      <p>🤵 신랑: 수빈 010-7676-6059</p>
      <p>👰 신부: 예림 010-8567-6059</p>
      <p>💳 계좌번호: 3333-32-2026635 (카카오뱅크)</p>
    </div>

    <!-- Action Buttons -->
    <div class="buttons">
      <a href="tel:01076766059" class="btn">전화하기</a>
      <a href="https://map.kakao.com/link/to/더아리엘" class="btn">오시는 길</a>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
   귀한 걸음 하셔서 저희의 시작을 축복해주세요😊
  </div>

</body>
</html>
