Portfolio Onepage - 배포 패키지
--------------------------------
포함 파일:
- index.html  (원페이지 웹사이트)
- README.txt  (배포 안내)

빠른 배포 방법 (권장):
1) GitHub Pages
   - GitHub에 새 저장소 생성, 파일 업로드(push)
   - Settings > Pages에서 배포 브랜치 선택 (main/master)
   - 몇 분 후 공개 URL이 생성됩니다.

2) Netlify (드래그 앤 드롭)
   - https://app.netlify.com -> Sites -> New site -> Deploy manually -> drag & drop index.html 또는 zip 파일 업로드
   - 간단하고 무료 플랜으로 빠르게 배포 가능

3) Vercel
   - Vercel 계정 생성 후 프로젝트 연결 (GitHub)
   - 또는 Vercel CLI로 배포 가능

로컬에서 테스트:
- index.html 파일을 더블클릭해 브라우저에서 열면 로컬에서 동작 확인 가능합니다.
- 또는 단순 로컬 서버: python -m http.server 8000 (터미널에서 실행)

커스터마이즈 필요사항:
- [디자이너 이름], 이메일, 전화번호, 이력서 링크, 실제 이미지/비디오 경로를 교체하세요.
- YouTube 임베드된 예시는 데모용입니다. 실제 동영상 ID로 교체하세요.
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    /* 전체 배경 흰색 */
    body {
      background-color: white;
      color: black;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* 상단 메뉴 바 */
    nav {
      background-color: #28a745; /* 메뉴 바 녹색 */
      padding: 10px 20px;
      display: flex;
      justify-content: flex-start;
      gap: 10px;
    }

    /* 메뉴 버튼 */
    .menu-button {
      background-color: white;
      color: #28a745;
      border: none;
      padding: 8px 15px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      transition: 0.3s;
    }

    .menu-button:hover {
      background-color: #218838;
      color: white;
    }

    /* 본문 영역 */
    .content {
      padding: 50px 20px;
      text-align: center;
    }
  </style>
</head>
<body>
  <nav>
    <button class="menu-button">Home</button>
    <button class="menu-button">Portfolio</button>
    <button class="menu-button">Contact</button>
  </nav>

  <div class="content">
    <h1>Welcome to My Portfolio</h1>
    <p>GitHub Pages에서 호스팅되는 간단한 사이트 예제입니다.</p>
  </div>
</body>
</html>
