---
title: "About Me"
layout: false
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Me</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      margin: 0; padding: 0; background: #fff; color: #222;
    }
    .container {
      max-width: 720px;
      margin: 60px auto;
      padding: 0 20px;
    }
    .profile-header {
      text-align: center;
      border-bottom: 2px solid #ccc;
      padding-bottom: 20px;
      margin-bottom: 20px;
    }
    .profile-header h1 {
      font-size: 36px;
      margin: 0;
    }
    .profile-header p {
      font-size: 18px;
      margin: 5px 0;
    }
    .content {
      font-size: 20px;
      line-height: 1.8;
      margin-bottom: 30px;
    }
    /* 一般主標題 */
    .content h2 {
      color: #111;
      margin-top: 40px;
      text-align: left;
    }
    /* 副標題 */
    .project-title {
      font-size: 22px;
      font-weight: bold;
      color: #111;
      margin-bottom: 10px;
      text-align: left;
    }
    /* 段落左右對齊 */
    .content p {
      text-align: justify;
    }
    /* PDF 按鈕 */
    .pdf-button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #0366d6;
      color: #fff;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
    }
    .pdf-button:hover {
      background-color: #024fa2;
    }
    /* 🔴 指定紅色標題 */
    .red-title {
      color: #c40000;
    }
  </style>
</head>

<body>
  <div class="container">

    <!-- 個人資訊 -->
    <div class="profile-header">
      <h1>Siu King Sum Personal Website</h1>
      <p><strong>Email:</strong> <a href="mailto:Kingstonsiu20040801@gmail.com">Kingstonsiu20040801@gmail.com</a></p>
      <p><strong>Phone:</strong> 5703 0675</p>
      <p><strong>GitHub:</strong> <a href="https://github.com/siiiiiiiiiii" target="_blank">github.com/siiiiiiiiiii</a></p>
      <p><strong>College:</strong> Hong Kong Shue Yan University (Year 3)</p>
    </div>

    <!-- About Me -->
    <div class="content">
      <h2>About Me</h2>
      <p>I am a FinTech student with a passion for hedge funds. …</p>
      <p>I firmly believe that hedge funds don’t need passive learners — …</p>
    </div>

    <!-- Personal Growth -->
    <div class="content">
      <h2>Personal Growth</h2>
      <p>In my first year, I struggled with programming and mathematics …</p>
    </div>

    <!-- Certifications -->
    <div class="content">
      <h2>Certifications</h2>
      <p>IELTS Overall Band 6.5 … Passed HKSI Paper 1</p>
    </div>

    <!-- Side Projects -->
    <div class="content">
      <h2 class="red-title">Side Projects</h2>

      <!-- 1. Self‑Initiated Investment & Portfolio Management -->
      <h2 class="red-title">1. Self‑Initiated Investment & Portfolio Management</h2>
      <p>I began investing in my first year, using money‑weighted return (MWR) as my performance metric. …</p>
      <p>I firmly believe that great long‑term investors don’t rely on market predictions — …</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/11gKLdVnUSWhS5Hmr_qq_7RQm1dtSxJ-W/view?usp=sharing" target="_blank">📄 View Full Investment Report (Google Drive)</a></p>
    </div>

    <!-- Quantitative Trading Section -->
    <div class="content">
      <h2 class="red-title">2. Quantitative Trading & Data‑Driven Models</h2>

      <p class="project-title red-title">2.1: Cointegration‑Based Pairs Trading Model</p>
      <p>Built a Cointegration Pairs Trading Model …</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1ZEI7BnvRLfd9WSh-Igyba2ojisQhTBeQ/view?usp=sharing" target="_blank">📄 View Pairs Trading Model Report</a></p>

      <p class="project-title red-title">2.2: LSTM with Attention for Log‑Return Prediction</p>
      <p>Developed a financial time‑series forecasting model using LSTM with an Attention mechanism …</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1jb7uFNVDoQJ-iNd8m-ljK78geIbXG7_O/view?usp=sharing" target="_blank">📄 View Full Log‑Return Prediction Report</a></p>

      <p class="project-title red-title">2.3: Data‑Driven Investment Analysis</p>
      <p>Leveraged Python for data‑driven investment analysis to minimize emotional decision‑making …</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1MHoymH-IMFhudPipTb7sVVEVhxXZdu4h/view?usp=sharing" target="_blank">📄 View Full Analysis Report</a></p>
    </div>

  </div>
</body>
</html>
