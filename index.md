---
title: "About Me"
layout: false
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <!-- 这行必须在 head 里 -->
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    /* ✨ 全部 CSS 都在这里 */
    body {
      font-family: Roboto, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
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
      margin: 0 0 20px;
    }
    .profile-header .info {
      font-size: 18px;
      margin: 8px 0;
      line-height: 1.4;
    }
    .content {
      font-size: 18px;
      line-height: 1.6;
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
      margin: 20px 0 10px;
      text-align: left;
    }
    .content p {
      text-align: left;
    }
    .content ul {
      margin-left: 20px;
    }
    .content li {
      margin-bottom: 5px;
    }
    .pdf-button {
      display: inline-block;
      padding: 10px 20px;
      background: #0366d6;
      color: #fff;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
    }
    .pdf-button:hover {
      background: #024fa2;
    }

    /* —— 手机端强制覆盖 —— */
    @media (max-width: 768px) {
      .container {
        margin: 40px auto !important;
        padding: 0 12px !important;
      }
      .profile-header {
        padding: 0 4px !important;
        margin-bottom: 32px !important;
      }
      .profile-header h1 {
        font-size: 26px !important;
        line-height: 1.3 !important;
        margin-bottom: 12px !important;
      }
      .profile-header .info {
        font-size: 15px !important;
        line-height: 1.6 !important;
        margin: 6px 0 !important;
        display: block !important;
      }
      .content {
        font-size: 15px !important;
        line-height: 1.9 !important;
        margin-bottom: 40px !important;
      }
      .content p {
        margin-bottom: 20px !important;
      }
      .content h2,
      .project-title {
        margin: 24px 0 12px !important;
      }
      .pdf-button {
        display: block !important;
        width: 100% !important;
        margin: 18px 0 !important;
        padding: 14px 0 !important;
        font-size: 15px !important;
      }
    }
  </style>
</head>

<body>
  <nav style="position:sticky;top:0;background:#fff;border-bottom:1px solid #ddd;padding:12px 0;text-align:center;z-index:1000;">
    <a href="#about" style="margin:0 16px;text-decoration:none;color:#0366d6;font-weight:500;">About</a>
    <a href="#projects" style="margin:0 16px;text-decoration:none;color:#0366d6;font-weight:500;">Projects</a>
  </nav>

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
  <div id="about" class="content">
    <h2>About Me</h2>
    <p>As a FinTech student, I’ve built projects like a pairs trading model, an LSTM + attention forecasting system, and a cryptocurrency (SiuToken). I’ve managed HKD 320,000 in real capital with consistent gains, limiting this year’s drawdown to –3.99 % versus the S&P 500’s –8.25 %.</p>
    <p>I'm good at using open‑source tools and AI to quickly build and test strategies. I review all my code myself and include reports with performance analysis.</p>
    <p>I care more about real experience than salary. I'm happy to start unpaid if it means I can learn and contribute to strategy and hands-on work. If you find my work valuable later, we can talk about pay or joining the team!</p>
    <p>All projects are open‑sourced on <a href="https://github.com/siiiiiiiiiii" target="_blank">GitHub</a> and on my <a href="https://siiiiiiiiiii.github.io/siiiiiiiii.github.io/" target="_blank">personal website</a>.</p>
  </div>

  <!-- Academic Growth -->
  <div class="content">
    <h2>Academic Growth</h2>
    <p>I struggled with programming and math during my first year, resulting in a GPA of 2.5. Since then, I’ve raised it above 3.7, earning straight A’s in core tech courses.</p>
  </div>

  <!-- Certifications -->
  <div class="content">
    <h2>Certifications</h2>
    <p>IELTS Overall Band: 6.5 (Listening 7, Reading 7, Writing 6.5, Speaking 6); currently focusing on improving speaking; Passed HKSI Paper 1</p>
  </div>

  <!-- Side Projects -->
  <div class="content">
    <h2>Side Projects</h2>

    <h2>1. Self‑Initiated Investment & Portfolio Management</h2>
    <p>I began investing in my first year, using money‑weighted return (MWR) as my performance metric. I achieved a 9 % return in the first year and improved to 20 % in the second. In the third year, I expanded into both U.S. and Chinese markets, allocating capital to recession‑resistant assets, limiting each stock to 1–5 % of total portfolio value to mitigate macroeconomic volatility. As of April 15, I successfully limited this year’s drawdown to –3.99 %, compared to S&P 500 (–8.25 %), NASDAQ (–12.88 %), and Nikkei (–14.1 %). My portfolio peaked at HKD 320,000, including a six‑figure sum entrusted solely to me by my father.</p>
    <p>I firmly believe that great long‑term investors don’t rely on market predictions — they rely on asset allocation to weather the storm.</p>
    <p><a class="pdf-button" href="https://drive.google.com/file/d/11gKLdVnUSWhS5Hmr_qq_7RQm1dtSxJ-W/view?usp=sharing" target="_blank">📄 View Investment Report</a></p>
  </div>

  <!-- Quantitative Trading & Data‑Driven Models -->
  <div id="projects" class="content">
    <h2>2. Quantitative Trading & Data‑Driven Models</h2>

    <!-- 2.1: Cointegration-Based Pairs Trading Model -->
    <p class="project-title">2.1: Cointegration‑Based Pairs Trading Model</p>
    <p>Built a cointegration‑based pairs trading model using Johansen test, OLS hedge ratio, ATR stop‑loss, volatility targeting, and parameter optimization.</p>
    <ul>
      <li>Backtest: 6.27 % return, 0.68 Sharpe, –8.67 % max drawdown</li>
      <li>Out‑of‑sample: 8.64 % return, 0.80 Sharpe, no overfitting</li>
      <li>Lower return than Buy‑and‑Hold, but far better risk control and market‑neutral alpha</li>
    </ul>
    <p><a class="pdf-button" href="https://drive.google.com/file/d/1ZEI7BnvRLfd9WSh-Igyba2ojisQhTBeQ/view?usp=sharing" target="_blank">📄 View Pairs Trading Report</a></p>

    <p class="project-title">2.2: LSTM with Attention for Log‑Return Prediction</p>
    <p>Developed a financial time‑series forecasting model using LSTM with an Attention mechanism. It converged stably within 100 epochs, with training and validation losses closely overlapping — no sign of over‑fitting. On the test set, it achieved MAE = 0.0127 and RMSE = 0.0176, significantly outperforming the Naive Baseline (RMSE = 0.0248).</p>
    <p><a class="pdf-button" href="https://drive.google.com/file/d/1jb7uFNVDoQJ-iNd8m-ljK78geIbXG7_O/view?usp=sharing" target="_blank">📄 View LSTM Report</a></p>

    <p class="project-title">2.3: Data‑Driven Investment Analysis</p>
    <p>Leveraged Python for data‑driven investment analysis to minimize emotional decision‑making. Applications include valuation comparisons between U.S. and Chinese markets and market sentiment analysis.</p>
    <p><a class="pdf-button" href="https://drive.google.com/file/d/1MHoymH-IMFhudPipTb7sVVEVhxXZdu4h/view?usp=sharing" target="_blank">📄 View Analysis Report</a></p>
  </div>

  <!-- Blockchain & DAO Smart Contract -->
  <div class="content">
    <h2>3. Blockchain & DAO Smart Contract</h2>
    <p>Developed the “SiuToken” (cryptocurrency) on the Sepolia testnet, implementing token locking, airdrops, dynamic transaction fees, and DAO voting. Conducted multiple rounds of testing using Remix IDE and MetaMask, demonstrating smart contract development experience.</p>
    <p><a class="pdf-button" href="https://drive.google.com/file/d/1kzNSA65TYckU7EwFObXPmiH8538xVpIG/view?usp=sharing" target="_blank">📄 View SiuToken & SiuDAO Report</a></p>
  </div>

  <!-- Other GitHub Projects -->
  <div class="content">
    <h2>4. Other GitHub Projects</h2>

    <p class="project-title">4.1: TradingView Modeling & Early Overfitting Awareness</p>
    <p>My early TradingView models overfit, teaching me that generalization matters most. Since then, I always prioritize avoiding overfitting.</p>
    <p><a class="pdf-button" href="https://github.com/siiiiiiiiiii/pine-scripts" target="_blank">🔗 View Pine‑Script on GitHub</a></p>

    <p class="project-title">4.2: Data Mining Model</p>
    <p>Built a data mining model for Amazon headphones and laptops. The decision tree achieved strong performance with an accuracy of 0.82, precision 0.79, recall 0.71, and an F1‑score of 0.75.</p>
    <p><a class="pdf-button" href="https://drive.google.com/file/d/1l8AJyxC15KGzFU1iqbkTjp2ZIWRHNMOD/view?usp=sharing" target="_blank">📄 View Full Data Mining Report</a></p>

    <p class="project-title">4.3: AAPL Stock Price Website</p>
    <p>Built an AAPL stock price website with technical indicators and interactive features.</p>
    <p><a class="pdf-button" href="https://github.com/siiiiiiiiiii/AAPL-stock-price-website" target="_blank">🔗 View on GitHub</a></p>

    <p class="project-title">4.4: Website Development Experience</p>
    <p>The website you are viewing right now was built by me personally.</p>
    <p><a class="pdf-button" href="https://github.com/siiiiiiiiiii/siiiiiiiii.github.io" target="_blank">🔗 View on GitHub</a></p>
  </div>

  <!-- Kaggle -->
  <div class="content">
    <h2>5. Kaggle</h2>
    <p>In the Titanic and House Prices competitions, I achieved 78.5 % accuracy (ranked 2,300) and 0.12507 RMSE (ranked 643), respectively. I realized that for small datasets, deeply understanding the data and crafting high‑quality features is more effective than blindly using complex neural networks or stacked models. This experience helped me develop a more pragmatic approach to machine learning.</p>
    <p><a class="pdf-button" href="https://github.com/siiiiiiiiiii/kaggle-Titanic-and-House-Prices-competitions-" target="_blank">🔗 View on GitHub</a></p>
  </div>

</div>
<hr>
<footer style="text-align:center; font-size:12px; color:#777; margin-top:40px;">
  © 2025 Siu King Sum. | Contact: Kingstonsiu20040801@gmail.com
</footer>
</body>
</html>
