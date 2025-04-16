---
layout: none
title: "About Me"
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #fff;
      color: #222;
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
      padding: 0;
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
    .content img {
      display: block;
      margin-top: 20px;
      margin-left: 0;
      max-width: 600px;
      width: 100%;
      height: auto;
    }
    .project-title {
      font-size: 22px;
      font-weight: bold;
      color: #111;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- 個人資訊卡 -->
    <div class="profile-header">
      <h1>Siu King Sum Personal Website</h1>
      <p><strong>Email:</strong> <a href="mailto:Kingstonsiu20040801@gmail.com">Kingstonsiu20040801@gmail.com</a></p>
      <p><strong>Phone:</strong> 5703 0675</p>
      <p><strong>GitHub:</strong> <a href="https://github.com/siiiiiiiiiii" target="_blank">github.com/siiiiiiiiiii</a></p>
      <p><strong>College:</strong> Hong Kong Shue Yan University (Year 3)</p>
    </div>

    <!-- About Me -->
    <div class="content">
      <h2>About Me</h2>
      <p>
        I am a student studying FinTech, and I have a strong interest in hedge funds. Even though my school courses don’t match the real world and I had little support, I chose to push myself. I taught myself and finished many projects on finance and blockchain, such as portfolio management, building trading models, creating DAOs and cryptocurrencies. I did everything by myself and shared my work on GitHub and my personal website. I once managed HKD 320,000 on my own, investing in both the US and China markets with full risk control.
      </p>
      <p>
        I believe hedge funds need people who take action, solve problems, and keep improving — even when working alone. I want to grow through real experience and turn my skills into something useful for a team.
      </p>
    </div>

    <!-- Personal Growth -->
    <div class="content">
      <h2>Personal Growth</h2>
      <p>
        In my first year, I was afraid of coding and math, so my GPA was only 2.5. Later, I worked hard and raised it to over 3.7+, getting A grades in all core tech subjects. More important than grades, my real growth is shown by managing HKD 320,000 in assets and completing several finance and blockchain projects.
      </p>
    </div>

    <!-- Certificates -->
    <div class="content">
      <h2>Certificates</h2>
      <p>
        IELTS score: 6.5 (Listening 7, Reading 7, Writing 6.5, Speaking 6). Now focusing on improving speaking; Passed HKSI Paper 1.
      </p>
    </div>

    <!-- Projects -->
    <div class="content">
      <h2>Technical & Investment Projects</h2>
      <p class="project-title">1: Self-Initiated Investment & Portfolio Management</p>
      <p>
        I began investing in my first year of university, using the money-weighted return as a performance metric. In the first year, I achieved a 9% return, increasing to 20% in the second year. In the third year, I expanded into both the U.S. and Chinese markets, allocating to recession-resilient assets while ensuring each stock accounted for only 1–5% of the portfolio.
      </p>
      <p>
        I firmly believe that great long-term investors don't rely on predicting the market, but on asset allocation to weather any storm!
      </p>
      <p>
        If you would like a more in-depth look at my investment experience, please see my full report here:
      </p>
      <p>
        👉 <a href="{{ '/assets/Report_Investment.pdf' | relative_url }}" target="_blank"><strong>Report_Investment.pdf</strong></a>
      </p>
      <p>Or view it embedded below:</p>
      <object data="{{ '/assets/Report_Investment.pdf' | relative_url }}" type="application/pdf" width="100%" height="800px">
        <p>Your browser does not support PDFs.
           <a href="{{ '/assets/Report_Investment.pdf' | relative_url }}" target="_blank">Download the PDF</a>.
        </p>
      </object>
    </div>
  </div>
</body>
</html>
