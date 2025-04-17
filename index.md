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
    .content h2 {
      color: #111;
      margin-top: 40px;
      text-align: left;
    }
    .project-title {
      font-size: 22px;
      font-weight: bold;
      color: #111;
      margin-bottom: 10px;
      text-align: left;
    }
    .content p {
      text-align: justify;
    }
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
      <p>I am a FinTech student with a passion for hedge funds. Faced with the disconnect between coursework and real‑world application, as well as a lack of resources and support, I chose to push beyond limitations through self‑learning. I independently completed multiple projects in finance and blockchain — from portfolio management to quantitative model development, and even DAO and cryptocurrency design — all of which I personally built and open‑sourced on GitHub and my personal website. At one point, I managed assets totaling HKD 320,000, spanning both U.S. and Chinese markets with full responsibility for risk control and execution.</p>
      <p>I firmly believe that hedge funds don’t need passive learners — they need individuals who can solve problems independently, keep improving, and forge a path even when working alone. I am eager to grow through hands‑on experience and turn my abilities into tangible value for a team.</p>
    </div>

    <!-- Personal Growth -->
    <div class="content">
      <h2>Personal Growth</h2>
      <p>In my first year, I struggled with programming and mathematics, resulting in a GPA of only 2.5. Since then, I have raised it to above 3.7+, achieving A grades in all core technology courses. More than grades, it is my continuous self‑improvement and real‑world accomplishments — including managing a HKD 320,000 portfolio and completing multiple finance and blockchain projects — that truly reflect my determination.</p>
    </div>

    <!-- Certifications -->
    <div class="content">
      <h2>Certifications</h2>
      <p>IELTS Overall Band: 6.5 (Listening 7, Reading 7, Writing 6.5, Speaking 6); currently focusing on improving speaking; Passed HKSI Paper 1</p>
    </div>

    <!-- Side Projects -->
    <div class="content">
      <h2 class="red-title">Side Projects</h2>

      <!-- 1. Self‑Initiated Investment & Portfolio Management -->
      <h2>1. Self‑Initiated Investment & Portfolio Management</h2>
      <p>I began investing in my first year, using money‑weighted return (MWR) as my performance metric. I achieved a 9% return in the first year and improved to 20% in the second. In the third year, I expanded into both U.S. and Chinese markets, allocating capital to recession‑resistant assets, limiting each stock to 1–5% of total portfolio value to mitigate macroeconomic volatility. As of April 15, I successfully limited this year’s drawdown to –3.99%, compared to S&P 500 (–8.25%), NASDAQ (–12.88%), and Nikkei (–14.1%). My portfolio peaked at HKD 320,000, including a six‑figure sum entrusted solely to me by my father — a strong vote of confidence in my asset‑management skills, risk‑control awareness, and sense of fiduciary responsibility.</p>
      <p>I firmly believe that great long‑term investors don’t rely on market predictions — they rely on asset allocation to weather the storm.</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/11gKLdVnUSWhS5Hmr_qq_7RQm1dtSxJ-W/view?usp=sharing" target="_blank">📄 View Full Investment Report (Google Drive)</a></p>
    </div>

    <!-- Quantitative Trading Section -->
    <div class="content">
      <h2>2. Quantitative Trading & Data‑Driven Models</h2>

      <!-- 2.1 Pairs Trading -->
      <p class="project-title">2.1: Cointegration‑Based Pairs Trading Model</p>
      <p>Built a Cointegration Pairs Trading Model, incorporating Johansen cointegration test, OLS hedge ratio, ATR‑based stop loss, target volatility leverage adjustment, and multi‑stage parameter optimization. In a 6‑year backtest, the model achieved an annualized return of 6.27%, annualized volatility of 9.21%, a Sharpe Ratio of 0.68, a Sortino Ratio of 0.78, and a maximum drawdown of –8.67%, demonstrating risk control.</p>
      <p>During out‑of‑sample testing, the model performed better than during training: annualized return 8.64%, Sharpe Ratio 0.80, while keeping drawdown stable — indicating no over‑fitting.</p>
      <p>Compared with Buy‑and‑Hold (24.32% return, 28.74% volatility, –40.54% drawdown), the strategy delivered lower risk (9.21% volatility, –8.67% drawdown) and full market neutrality, providing stable long‑term gains.</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1ZEI7BnvRLfd9WSh-Igyba2ojisQhTBeQ/view?usp=sharing" target="_blank">📄 View Pairs Trading Model Report</a></p>

      <!-- 2.2 LSTM with Attention -->
      <p class="project-title">2.2: LSTM with Attention for Log‑Return Prediction</p>
      <p>Developed a financial time‑series forecasting model using LSTM with an Attention mechanism. It converged stably within 100 epochs, with training and validation losses closely overlapping — no sign of over‑fitting. On the test set, it achieved MAE = 0.0127 and RMSE = 0.0176, significantly outperforming the Naive Baseline (RMSE = 0.0248).</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1jb7uFNVDoQJ-iNd8m-ljK78geIbXG7_O/view?usp=sharing" target="_blank">📄 View Full Log‑Return Prediction Report</a></p>

      <!-- 2.3 Data‑Driven Investment Analysis -->
      <p class="project-title">2.3: Data‑Driven Investment Analysis</p>
      <p>Leveraged Python for data‑driven investment analysis to minimize emotional decision‑making. Applications include valuation comparisons between U.S. and Chinese markets and market sentiment analysis.</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1MHoymH-IMFhudPipTb7sVVEVhxXZdu4h/view?usp=sharing" target="_blank">📄 View Full Analysis Report</a></p>
    </div>

  </div>
</body>
</html>
