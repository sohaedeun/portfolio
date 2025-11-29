<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    /* 전체 배경 흰색, 글자 검정 */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: white;
      color: black;
    }

    /* 상단 네비게이션 바 */
    nav {
      background-color: #28a745; /* 녹색 메뉴 바 */
      padding: 10px 20px;
      display: flex;
      gap: 10px;
    }

    /* 메뉴 버튼 */
    .menu-button {
      background-color: white;
      color: #28a745;
      border: none;
      padding: 8px 15px;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    .menu-button:hover {
      background-color: #218838; /* 호버 시 진한 녹색 */
      color: white;
    }

    /* 메인 컨텐츠 */
    .hero {
      padding: 100px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }

    /* 섹션 스타일 */
    section {
      padding: 50px 20px;
      text-align: center;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    section p {
      font-size: 1rem;
      max-width: 600px;
      margin: 0 auto;
    }
  </style>
</head>
<body>

  <!-- 네비게이션 -->
  <nav>
    <button class="menu-button">Home</button>
    <button class="menu-button">Portfolio</button>
    <button class="menu-button">About</button>
    <button class="menu-button">Contact</button>
  </nav>

  <!-- 히어로 영역 -->
  <div class="hero">
    <h1>Welcome to My Portfolio</h1>
    <p>여기는 나의 디자인 & 영상 포트폴리오 사이트입니다. GitHub Pages를 통해 배포되었습니다.</p>
  </div>

  <!-- 포트폴리오 섹션 -->
  <section>
    <h2>Portfolio</h2>
    <p>여기에 프로젝트 썸네일이나 영상 링크를 추가할 수 있습니다.</p>
  </section>

  <!-- About 섹션 -->
  <section>
    <h2>About Me</h2>
    <p>간단한 자기소개를 적고, 연락처나 SNS 링크도 추가할 수 있습니다.</p>
  </section>

  <!-- Contact 섹션 -->
  <section>
    <h2>Contact</h2>
    <p>이메일: example@email.com</p>
    <p>GitHub: <a href="https://github.com/sohaedeun" target="_blank">sohaedeun</a></p>
  </section>

</body>
</html>
