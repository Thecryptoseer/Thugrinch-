index.html<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Thugrinch | Power to the Holders</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: radial-gradient(circle at top, #0f0f0f, #000);
      color: #ffffff;
    }
    header {
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 3.2rem;
      margin-bottom: 10px;
      color: #00ff99;
      letter-spacing: 2px;
    }
    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }
    .btn {
      display: inline-block;
      margin: 12px;
      padding: 14px 30px;
      background: #00ff99;
      color: #000;
      text-decoration: none;
      font-weight: bold;
      border-radius: 10px;
    }
    .btn.alt {
      background: transparent;
      border: 2px solid #00ff99;
      color: #00ff99;
    }
    section {
      padding: 70px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .card {
      background: #0b0b0b;
      padding: 35px;
      border-radius: 20px;
      margin-bottom: 35px;
      box-shadow: 0 15px 40px rgba(0,0,0,0.6);
    }
    .card h2 {
      color: #00ff99;
      margin-bottom: 15px;
    }
    .countdown {
      font-size: 2rem;
      margin-top: 20px;
      color: #00ff99;
    }
    .tokenomics ul {
      list-style: none;
      padding: 0;
    }
    .tokenomics li {
      padding: 10px 0;
      border-bottom: 1px solid #1a1a1a;
    }
    iframe {
      width: 100%;
      height: 400px;
      border-radius: 16px;
      border: none;
      background: #000;
    }
    footer {
      text-align: center;
      padding: 40px 20px;
      background: #000;
      font-size: 0.9rem;
      opacity: 0.7;
    }
  </style>
</head>
<body><header>
  <h1>THUGRINCH</h1>
  <p>Stealing Liquidity From Bears • Giving Power to Holders</p>
  <div class="countdown" id="countdown">Loading countdown...</div>
  <a href="#buy" class="btn">Buy Thugrinch</a>
  <a href="#tokenomics" class="btn alt">Tokenomics</a>
</header><section id="about">
  <div class="card">
    <h2>What is Thugrinch?</h2>
    <p>
      Thugrinch is a Solana-based memecoin powered by culture, memes, and raw street energy. 
      No empty promises. No weak hands. Just dominance, community, and execution.
    </p>
  </div>  <div class="card">
    <h2>The Thugrinch Mentality</h2>
    <p>
      • Holders come first 💪<br>
      • Bears are the exit liquidity 🐻❌<br>
      • Community controls the narrative 🔥<br>
      • Memes backed by conviction 🚀
    </p>
  </div>
</section><section id="tokenomics">
  <div class="card tokenomics">
    <h2>Tokenomics</h2>
    <ul>
      <li>Total Supply: 1,000,000,000 THUG</li>
      <li>Liquidity: Locked 🔒</li>
      <li>Taxes: 0%</li>
      <li>Chain: Solana</li>
      <li>Ownership: Renounced</li>
    </ul>
  </div>
</section><section id="buy">
  <div class="card">
    <h2>How to Buy</h2>
    <p>
      1. Install a Solana wallet (Phantom / Solflare)<br>
      2. Load SOL<br>
      3. Buy on Raydium or Pump.fun<br>
      4. Hold like a thug 💎
    </p>
    <a href="#" class="btn">Buy on Raydium</a>
    <a href="#" class="btn alt">Buy on Pump.fun</a>
  </div>
</section><section id="chart">
  <div class="card">
    <h2>Live Chart</h2>
    <iframe src="about:blank" title="Live Chart Placeholder"></iframe>
    <p style="opacity:0.6">Chart will auto-load once token is live.</p>
  </div>
</section><section id="community">
  <div class="card">
    <h2>Join the Community</h2>
    <p>
      Thugrinch is nothing without the people. Holders are the backbone. Memes are the weapon.
    </p>
    <a href="#" class="btn">X (Twitter)</a>
    <a href="#" class="btn alt">Telegram</a>
  </div>
</section><section id="holders">
  <div class="card">
    <h2>Holder Power</h2>
    <p>
      The strength of Thugrinch is measured by its holders. No insiders. No cabal. Just conviction.
    </p>
    <h3 style="color:#00ff99;font-size:2rem;">👥 0+ Holders</h3>
    <p style="opacity:0.6">(Auto-updates once token is live)</p>
  </div>
</section><section id="wallet">
  <div class="card">
    <h2>Connect Wallet</h2>
    <p>
      Connect your Solana wallet to prepare for launch. Phantom & Solflare supported.
    </p>
    <button class="btn" onclick="alert('Wallet connect activates once deployed & token is live');">Connect Wallet</button>
  </div>
</section><section id="trust">
  <div class="card">
    <h2>Why You Can Trust Thugrinch</h2>
    <p>
      • Liquidity locked 🔒<br>
      • Contract renounced ✅<br>
      • Zero taxes 💯<br>
      • Community-owned narrative 🧠<br>
      • No roadmap lies ❌
    </p>
  </div>
</section><section id="memes">
  <div class="card">
    <h2>Meme Vault</h2>
    <p>
      Memes fuel the mission. This vault will be filled with community-made Thugrinch content.
    </p>
    <p style="opacity:0.6">(Gallery unlocks post-launch)</p>
  </div>
</section><footer>
  © 2025 Thugrinch. Built for holders. Powered by memes.
</footer><script>
  // COUNTDOWN TIMER (SET LAUNCH DATE HERE)
  const launchDate = new Date("2025-12-27T20:00:00Z").getTime();
  const countdownEl = document.getElementById("countdown");

  setInterval(() => {
    const now = new Date().getTime();
    const distance = launchDate - now;

    if (distance < 0) {
      countdownEl.innerHTML = "🚀 THUGRINCH IS LIVE";
      return;
    }

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    countdownEl.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
  }, 1000);
</script></body>
</html>