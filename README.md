<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }
    header {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      margin: 5px 0;
      font-size: 1.2em;
    }
    .container {
      max-width: 900px;
      margin: 20px auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    .section-title {
      font-size: 1.5em;
      margin: 20px 0 10px;
      border-bottom: 2px solid #2c3e50;
      padding-bottom: 5px;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .badge {
      padding: 10px 15px;
      background-color: #2c3e50;
      color: white;
      border-radius: 4px;
      font-size: 0.9em;
      text-align: center;
    }
    ul {
      padding-left: 20px;
    }
    ul li {
      margin-bottom: 5px;
    }
    .contact a {
      text-decoration: none;
      color: #2c3e50;
      font-weight: bold;
    }
    .contact a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>이준혁</h1>
    <p>메카트로닉스 공학부 | 인공지능응용학전공</p>
  </header>

  <div class="container">
    <div class="section">
      <h2 class="section-title">📚 Education</h2>
      <p>2016 - 2019: 나주고등학교 졸업</p>
      <p>2019 - 2023: 호서대학교 빅데이터 경영공학과</p>
      <p>2023 - 2025: 한국공학대학교 메카트로닉스 전공 (편입)</p>
    </div>

    <div class="section">
      <h2 class="section-title">💼 Career</h2>
      <p>2019.04 - 2020.12: 호서대학교 단과대 학생회 - 기획회원</p>
      <p>2020.12 - 2021.04: 육군 39사단 117여단 통신소대 분대장</p>
      <p>2024.03 - 현재: CIR 동아리 - 기획부장 및 조교</p>
    </div>

    <div class="section">
      <h2 class="section-title">✨ Skills</h2>
      <div class="skills">
        <span class="badge">Python</span>
        <span class="badge">C / C++</span>
        <span class="badge">ROS1 / ROS2</span>
        <span class="badge">TensorFlow</span>
        <span class="badge">PyTorch</span>
        <span class="badge">OpenCV</span>
        <span class="badge">MySQL</span>
        <span class="badge">Ubuntu</span>
      </div>
    </div>

    <div class="section">
      <h2 class="section-title">🏆 Competitions</h2>
      <ul>
        <li>한국공학대 - 아두이노 챌린지 (본선)</li>
        <li>2023 국제로봇콘테스트 - 씨로봇 (본선)</li>
        <li>2024 메카이브 창작 메이커톤 (최우수상)</li>
      </ul>
    </div>

    <div class="section">
      <h2 class="section-title">📫 Contact</h2>
      <div class="contact">
        <a href="mailto:leejh104@naver.com">Email: leejh104@naver.com</a>
        <p>Phone: 010-5240-2729</p>
      </div>
    </div>
  </div>
</body>
</html>
