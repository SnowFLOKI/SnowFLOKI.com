# SnowFLOKI.com <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SnowFLOKI — Chill, Meme & Moon</title>

  <!-- Link to external stylesheet -->
  <link href="styles.css" rel="stylesheet" />
</head>
<body>

  <!-- Hero / Banner section (top of the page) -->
  <header class="hero">
    <div class="hero-overlay">
      <h1>SnowFLOKI 🐶❄️</h1>
      <p>Chill. Meme. Moon — The Meme Coin Built to Outlast the Seasons</p>
      <!-- CTA (Call To Action) button — “join the pack / buy” -->
      <a href="#join" class="btn-primary">Join the Pack</a>
    </div>
  </header>

  <main>
    <!-- About section -->
    <section id="about">
      <h2>About SnowFLOKI</h2>
      <p>SnowFLOKI is a community‑driven meme coin for those who believe in long‑term vision, loyalty, and fun. Born from the frozen North, it aims to build a global pack — not just a quick pump.</p>
    </section>

    <!-- Narrative / Vision section -->
    <section id="narrative">
      <h2>Why SnowFLOKI ❄️🐶</h2>
      <p><em>SnowFLOKI: The Meme Coin Built to Outlast the Seasons</em></p>
      <p>In a world full of meme coins that burn bright and disappear fast, SnowFLOKI was born with a different destiny. He didn’t emerge from hype — he emerged from endurance.</p>
      <p>SnowFLOKI isn’t chasing quick pumps. He’s building long‑term momentum — slow, steady, unstoppable.</p>
      <blockquote>“Hype creates a moment. Community creates a legacy.”</blockquote>
      <p>When the market warms again? SnowFLOKI will be the one leading the thaw — with the strongest, most loyal pack behind him.</p>
      <p><strong>SnowFLOKI: Born for the long game. Forged by winter. Driven by community. Built to last.</strong></p>
    </section>

    <!-- Tokenomics section: shows supply and allocation -->
    <section id="tokenomics">
      <h2>Tokenomics</h2>
      <div class="tokenomics-grid">
        <div class="tok-card"><div class="big">1,000,000,000</div><div class="label">Total Supply</div></div>
        <div class="tok-card"><div class="big">60%</div><div class="label">Liquidity</div></div>
        <div class="tok-card"><div class="big">25%</div><div class="label">Community & Marketing</div></div>
        <div class="tok-card"><div class="big">10%</div><div class="label">Team (locked / vesting)</div></div>
        <div class="tok-card"><div class="big">5%</div><div class="label">Reserve / Burn / Future Use</div></div>
      </div>
    </section>

    <!-- Roadmap & Vision timeline -->
    <section id="roadmap">
      <h2>Roadmap & Vision</h2>
      <ol>
        <li><strong>Phase 1 – Awareness & Community Building:</strong> Social campaigns, influencer outreach, listing on trackers, community growth.</li>
        <li><strong>Phase 2 – Token Utility & Support:</strong> Buyback & burn, staking/reward systems, partnerships (NFTs, gaming, etc.).</li>
        <li><strong>Phase 3 – Listings & Liquidity:</strong> Target CEX listings, cross‑chain support, liquidity‑mining events.</li>
        <li><strong>Phase 4 – Long-Term Growth & Ecosystem:</strong> Governance, merch/NFTs, gamified experiences, sustained community engagement.</li>
      </ol>
    </section>

    <!-- Join / Buy section -->
    <section id="join">
      <h2>Join the Pack / Buy SnowFLOKI</h2>
      <p>Connect your wallet (e.g. MetaMask), swap via supported DEX, then hold, stake, or add liquidity. Always double‑check the contract address before trading.</p>
      <a href="#" class="btn-primary">Get SnowFLOKI</a>
    </section>

    <!-- Community & Social links -->
    <section id="contact">
      <h2>Community & Socials</h2>
      <p>Stay updated and connect with us on Telegram and X.</p>
      <div class="social-icons">
        <a href="https://t.me/+jzYcNr94wIs1ZDVl" target="_blank" rel="noopener noreferrer">Telegram</a>
        <a href="https://x.com/SnowFLOKI100" target="_blank" rel="noopener noreferrer">X</a>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <div class="footer-text">&copy; 2025 SnowFLOKI. All rights reserved.</div>
  </footer>

  <!-- Optional: snow effect script -->
  <script src="snow.js"></script>

</body>
</html>
/* Importing custom font from Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

/* Reset default margins/paddings, set box sizing */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Base body styling: background gradient, font, text color */
body {
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #0a1f3d 0%, #1e3b6e 100%);
  color: #fff;
}

/* Hero / banner section styling */
.hero {
  position: relative;
  text-align: center;
  padding: 120px 20px;
  background: #1e3b6e; /* can replace with image background if you add mascot/logo */
}

/* Hero title */
.hero h1 {
  font-size: 3.5rem;
  margin-bottom: 20px;
  letter-spacing: 2px;
}

/* Hero subtitle / tagline */
.hero p {
  font-size: 1.3rem;
  opacity: 0.9;
  margin-bottom: 30px;
}

/* CTA button styling — shared for buttons */
.btn-primary {
  background: #4dcaff;
  color: #0a1f3d;
  padding: 16px 36px;
  font-size: 1.1rem;
  font-weight: 600;
  border: none;
  border-radius: 8px;
  text-decoration: none;
  display: inline-block;
  transition: background 0.3s;
}
.btn-primary:hover {
  background: #33c0ff;
}

/* Main content area styling */
main {
  padding: 40px 20px;
  max-width: 900px;
  margin: 0 auto;
}

/* Section spacing */
section {
  margin-bottom: 60px;
}

/* Section heading style */
section h2 {
  font-size: 2.2rem;
  border-bottom: 3px solid #4dcaff;
  display: inline-block;
  padding-bottom: 8px;
  margin-bottom: 24px;
}

/* Tokenomics grid — responsive cards layout */
.tokenomics-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 24px;
}

.tok-card {
  background: rgba(255,255,255,0.12);
  border: 1px solid rgba(255,255,255,0.3);
  border-radius: 14px;
  padding: 28px 20px;
  text-align: center;
  transition: background 0.3s, transform 0.3s;
}
.tok-card:hover {
  background: rgba(255,255,255,0.18);
  transform: translateY(-5px);
}

.tok-card .big {
  font-size: 2.4rem;
  font-weight: 700;
  margin-bottom: 8px;
}
.tok-card .label {
  font-size: 0.95rem;
  opacity: 0.85;
}

/* Blockquote styling for quotes / emphasis */
blockquote {
  font-style: italic;
  opacity: 0.9;
  border-left: 4px solid #4dcaff;
  padding-left: 12px;
  margin: 20px 0;
}

/* Social icons container (just links styled as simple text — can style more or replace with icons) */
.social-icons {
  margin-top: 16px;
}
.social-icons a {
  color: #fff;
  margin: 0 12px;
  font-size: 1.2rem;
  text-decoration: none;
  transition: transform 0.3s, color 0.3s;
}
.social-icons a:hover {
  transform: scale(1.2);
  color: #4dcaff;
}

/* Footer styling */
footer {
  text-align: center;
  padding: 40px 20px;
  opacity: 0.8;
  font-size: 0.9rem;
}
// Create a canvas element dynamically to draw snowflakes
const canvas = document.createElement('canvas');
canvas.id = 'snow';
document.body.appendChild(canvas);
const ctx = canvas.getContext('2d');

// Set initial width/height to window size
let w = canvas.width = window.innerWidth;
let h = canvas.height = window.innerHeight;
let particles = [];

// Initialize snow particles
function initSnow(count = 200) {
  particles = [];
  for (let i = 0; i < count; i++) {
    particles.push({
      x: Math.random() * w,          // x-coordinate (random across width)
      y: Math.random() * h,          // y-coordinate (random across height)
      r: Math.random() * 4 + 1,      // radius of snowflake
      d: Math.random() * 50,         // density (affects movement)
      speed: Math.random() * 1 + 0.5 // vertical falling speed
    });
  }
}

// Draw snowflakes on canvas
function drawSnow() {
  ctx.clearRect(0, 0, w, h);
  ctx.fillStyle = "rgba(255, 255, 255, 0.8)";
  ctx.beginPath();
  for (let p of particles) {
    ctx.moveTo(p.x, p.y);
    ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2, true);
  }
  ctx.fill();
  updateSnow();
}

// Update snow positions (falling effect)
let angle = 0;
function updateSnow() {
  angle += 0.01;
  for (let p of particles) {
    p.y += Math.cos(angle + p.d) + p.speed;
    p.x += Math.sin(angle) * 2;
    // reset snowflake if it goes beyond bottom
    if (p.y > h) {
      p.y = -p.r;
      p.x = Math.random() * w;
    }
  }
}

// Animation loop
function animateSnow() {
  drawSnow();
  requestAnimationFrame(animateSnow);
}

// Handle window resize
window.addEventListener('resize', () => {
  w = canvas.width = window.innerWidth;
  h = canvas.height = window.innerHeight;
  initSnow();
});

// Initialize and start snow effect
initSnow(200);
animateSnow();
