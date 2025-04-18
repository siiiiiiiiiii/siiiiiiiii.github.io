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
      margin: 0 0 20px; /* 下方留 20px 空白 */
    }
    .profile-header .info {
      font-size: 18px;
      margin: 8px 0;
      line-height: 1.4;
    }

    /* 內容排版 */
    .content       { font-size: 20px; line-height: 1.8; margin-bottom: 30px; }
    .content h2    { color:#111; margin-top:40px; text-align:left; }
    .project-title { font-size:22px; font-weight:bold; color:#111; margin-bottom:10px; text-align:left; }
    .content p     { text-align: justify; }

    /* 按鈕樣式 */
    .pdf-button {
      display:inline-block; padding:10px 20px; background:#0366d6; color:#fff;
      border-radius:6px; text-decoration:none; font-weight:bold; margin-top:10px;
    }
    .pdf-button:hover { background:#024fa2; }
  </style>
</head>

<body>
  <div class="container">

    <!-- 個人資訊 -->
    <div class="profile-header">
      <h1>Siu King Sum Personal Website</h1>
      <p class="info"><strong>Email:</strong> <a href="mailto:Kingstonsiu20040801@gmail.com">Kingstonsiu20040801@gmail.com</a></p>
      <p class="info"><strong>Phone:</strong> +852 5703 0675</p>
      <p class="info"><strong>GitHub:</strong> <a href="https://github.com/siiiiiiiiiii" target="_blank">github.com/siiiiiiiiiii</a></p>
      <p class="info"><strong>College:</strong> Hong Kong Shue Yan University (Year 3)</p>
    </div>

    <!-- About Me -->
    <div class="content">
      <h2>About Me</h2>

      <p>As a student majoring in FinTech, I have self‑studied and completed side projects such as a Pairs Trading Model, an LSTM + Attention prediction model, and the development of the “SiuToken” (a cryptocurrency). I have also managed assets up to HKD 320,000, consistently generating profits. Despite the market volatility this year, I managed to limit my losses to –3.99%, compared to the S&P 500’s decline of 8.25%.</p>

      <p>I excel at using open‑source tools and AI to accelerate the prototyping and testing of strategies. Every line of code is personally verified by me, accompanied by written reports and performance analysis. I believe true ability lies not in grades, but in the integration of financial logic and technical skills to create viable investment strategies.</p>

      <p>Rather than assisting in report writing at a large firm, I am more eager for an opportunity—paid or unpaid—that allows me to be deeply involved in strategy development and real‑world application. I’m willing to start without pay, just for the chance to truly learn and contribute. If later on you find my work valuable, then we can discuss compensation or even a spot on the team. To me, opportunity is more important than salary—real practice is the best proof of capability.</p>

      <p>All projects are open‑sourced on GitHub (<a href="https://github.com/siiiiiiiiiii" target="_blank">https://github.com/siiiiiiiiiii</a>) and on my personal website (<a href="https://siiiiiiiiiii.github.io/siiiiiiiii.github.io/" target="_blank">https://siiiiiiiiiii.github.io/siiiiiiiii.github.io/</a>).</p>
    </div>

    <!-- Personal Growth -->
    <div class="content">
      <h2>Personal Growth</h2>
      <p>In my first year, I struggled with programming and mathematics, resulting in a GPA of only 2.5. Since then, I have raised it to above 3.7+, achieving A grades in all core technology courses.</p>
    </div>

    <!-- Certifications -->
    <div class="content">
      <h2>Certifications</h2>
      <p>IELTS Overall Band: 6.5 (Listening 7, Reading 7, Writing 6.5, Speaking 6); currently focusing on improving speaking; Passed HKSI Paper 1</p>
    </div>

    <!-- Side Projects -->
    <div class="content">
      <h2>Side Projects</h2>

      <!-- 1. Self‑Initiated Investment -->
      <h2>1. Self‑Initiated Investment & Portfolio Management</h2>
      <p>I began investing in my first year, using money‑weighted return (MWR) as my performance metric. I achieved a 9% return in the first year and improved to 20% in the second. In the third year, I expanded into both U.S. and Chinese markets, allocating capital to recession‑resistant assets, limiting each stock to 1–5% of total portfolio value to mitigate macroeconomic volatility. As of April 15, I successfully limited this year’s drawdown to –3.99%, compared to S&P 500 (–8.25%), NASDAQ (–12.88%), and Nikkei (–14.1%). My portfolio peaked at HKD 320,000, including a six‑figure sum entrusted solely to me by my father — a strong vote of confidence in my asset‑management skills, risk‑control awareness, and sense of fiduciary responsibility.</p>
      <p>I firmly believe that great long‑term investors don’t rely on market predictions — they rely on asset allocation to weather the storm.</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/11gKLdVnUSWhS5Hmr_qq_7RQm1dtSxJ-W/view?usp=sharing" target="_blank">📄 View Investment Report</a></p>
    </div>

    <!-- Quantitative Trading -->
    <div class="content">
      <h2>2. Quantitative Trading & Data‑Driven Models</h2>

      <p class="project-title">2.1: Cointegration‑Based Pairs Trading Model</p>
      <p>Built a Cointegration Pairs Trading Model, incorporating Johansen cointegration test, OLS hedge ratio, ATR‑based stop loss, target volatility leverage adjustment, and multi‑stage parameter optimization …</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1ZEI7BnvRLfd9WSh-Igyba2ojisQhTBeQ/view?usp=sharing" target="_blank">📄 View Pairs Trading Report</a></p>

      <p class="project-title">2.2: LSTM with Attention for Log‑Return Prediction</p>
      <p>Developed a financial time‑series forecasting model using LSTM with an Attention mechanism …</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1jb7uFNVDoQJ-iNd8m-ljK78geIbXG7_O/view?usp=sharing" target="_blank">📄 View LSTM Report</a></p>

      <p class="project-title">2.3: Data‑Driven Investment Analysis</p>
      <p>Leveraged Python for data‑driven investment analysis to minimize emotional decision‑making …</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1MHoymH-IMFhudPipTb7sVVEVhxXZdu4h/view?usp=sharing" target="_blank">📄 View Analysis Report</a></p>
    </div>

    <!-- Blockchain & DAO -->
    <div class="content">
      <h2>3. Blockchain & DAO Smart Contract</h2>
      <p>Developed the “SiuToken” smart contract on the Sepolia testnet with features such as token locking, airdrops, dynamic fees, and DAO voting. Multiple test rounds were conducted via Remix IDE and MetaMask.</p>
      <p><a class="pdf-button" href="https://drive.google.com/file/d/1bvv8uCyk2G1N2vT7kfU-ygWDWt5QL-fZ/view?usp=sharing" target="_blank">📄 View SiuToken & SiuDAO Report</a></p>
    </div>

    <!-- Other GitHub Projects -->
    <div class="content">
      <h2>4. Other GitHub Projects</h2>

      <p class="project-title">4.1: TradingView Modeling & Early Overfitting Awareness</p>
      <p>In the early stages of self‑learning quantitative trading, I used TradingView for model development...</p>
      <p><a class="pdf-button" href="https://github.com/siiiiiiiiiii/pine-scripts" target="_blank">🔗 View Pine‑Script Models on GitHub</a></p>
    </div>

  </div>
</body>
</html>
