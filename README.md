<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Trade With Prateel Sahni</title>

<!-- META PIXEL CODE -->
<script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '1325268956141870');
fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=1325268956141870&ev=PageView&noscript=1"/></noscript>
<!-- END META PIXEL CODE -->

<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Syne:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}

:root{
  --gold:#F5C518;
  --gold2:#FFE066;
  --green:#00E5A0;
  --red:#FF4757;
  --bg:#04060C;
  --card:#080E1A;
  --border:rgba(245,197,24,0.12);
  --text:#F0F4FF;
  --muted:#5A6A82;
}

body{
  font-family:'Syne',sans-serif;
  background:var(--bg);
  color:var(--text);
  min-height:100vh;
  overflow-x:hidden;
}

/* ── ANIMATED BG ── */
.bg-layer{position:fixed;inset:0;z-index:0;pointer-events:none;}

.bg-grid{
  background-image:
    linear-gradient(rgba(245,197,24,0.04) 1px,transparent 1px),
    linear-gradient(90deg,rgba(245,197,24,0.04) 1px,transparent 1px);
  background-size:40px 40px;
}

.bg-radial{
  background:
    radial-gradient(ellipse 70% 50% at 50% 0%,rgba(245,197,24,0.09) 0%,transparent 60%),
    radial-gradient(ellipse 40% 30% at 50% 100%,rgba(0,229,160,0.06) 0%,transparent 60%);
}

/* Animated scan line */
.scanline{
  position:fixed;top:-4px;left:0;right:0;height:3px;
  background:linear-gradient(90deg,transparent,rgba(245,197,24,0.6),transparent);
  z-index:2;pointer-events:none;
  animation:scan 6s linear infinite;
  opacity:0.4;
}
@keyframes scan{
  0%{top:-4px;}100%{top:100vh;}
}

/* Floating orbs */
.orb{
  position:fixed;border-radius:50%;pointer-events:none;z-index:0;
  filter:blur(80px);opacity:0.12;
}
.orb1{width:400px;height:400px;background:var(--gold);top:-100px;left:-100px;animation:orbFloat1 12s ease-in-out infinite;}
.orb2{width:300px;height:300px;background:var(--green);bottom:-80px;right:-80px;animation:orbFloat2 15s ease-in-out infinite;}
.orb3{width:200px;height:200px;background:#7B61FF;top:40%;left:50%;transform:translate(-50%,-50%);animation:orbFloat3 10s ease-in-out infinite;}
@keyframes orbFloat1{0%,100%{transform:translate(0,0);}50%{transform:translate(40px,30px);}}
@keyframes orbFloat2{0%,100%{transform:translate(0,0);}50%{transform:translate(-30px,-40px);}}
@keyframes orbFloat3{0%,100%{transform:translate(-50%,-50%) scale(1);}50%{transform:translate(-50%,-50%) scale(1.3);}}

/* PARTICLES */
.particles{position:fixed;inset:0;pointer-events:none;z-index:1;overflow:hidden;}
.pt{position:absolute;border-radius:50%;opacity:0;animation:ptFloat linear infinite;}
@keyframes ptFloat{
  0%{transform:translateY(110vh) scale(0);opacity:0;}
  8%{opacity:1;}92%{opacity:0.3;}100%{transform:translateY(-50px) scale(1.5);opacity:0;}
}

/* ── TICKER ── */
.ticker-wrap{
  width:100%;overflow:hidden;
  background:rgba(245,197,24,0.05);
  border-bottom:1px solid var(--border);
  padding:8px 0;position:relative;z-index:10;
}
.ticker-track{display:flex;width:max-content;animation:tickerMove 28s linear infinite;}
.ti{
  padding:0 24px;font-size:11px;font-weight:700;
  letter-spacing:1px;color:var(--muted);
  border-right:1px solid var(--border);white-space:nowrap;
}
.ti span{margin-left:5px;}
.ti .up{color:var(--green);}
.ti .dn{color:var(--red);}
@keyframes tickerMove{0%{transform:translateX(0);}100%{transform:translateX(-50%);}}

/* ── MAIN WRAPPER ── */
.wrap{
  position:relative;z-index:5;
  max-width:450px;margin:0 auto;
  padding:0 22px 70px;
}

/* ── TOP STRIP ── */
.top-strip{
  display:flex;align-items:center;justify-content:center;gap:8px;
  padding:10px 0;
  margin-top:20px;
  animation:fadeUp 0.5s ease both;
}
.live-dot{
  width:8px;height:8px;background:var(--green);border-radius:50%;
  box-shadow:0 0 8px var(--green);
  animation:blink 1.2s ease-in-out infinite;
}
@keyframes blink{0%,100%{opacity:1;}50%{opacity:0.3;}}
.live-text{font-size:11px;font-weight:700;letter-spacing:2px;color:var(--green);text-transform:uppercase;}

/* ── HERO ── */
.hero{text-align:center;padding-top:12px;}

/* Avatar */
.av-wrap{width:110px;height:110px;margin:0 auto 18px;position:relative;}
.av-ring{
  position:absolute;inset:-6px;border-radius:50%;
  background:conic-gradient(var(--gold) 0%,var(--green) 33%,var(--gold2) 66%,var(--gold) 100%);
  animation:spinRing 2.5s linear infinite;z-index:0;
}
.av-mask{position:absolute;inset:-2px;border-radius:50%;background:var(--bg);z-index:1;}
.av-inner{
  position:absolute;inset:5px;border-radius:50%;z-index:2;
  background:linear-gradient(135deg,#0f1a2e,#070d18);
  display:flex;align-items:center;justify-content:center;font-size:40px;
  box-shadow:inset 0 2px 10px rgba(0,0,0,0.5);
}
.av-badge{
  position:absolute;bottom:0;right:0;
  width:26px;height:26px;
  background:linear-gradient(135deg,var(--green),#00b87a);
  border-radius:50%;border:3px solid var(--bg);z-index:3;
  display:flex;align-items:center;justify-content:center;
  font-size:11px;font-weight:800;color:#000;
  box-shadow:0 0 10px rgba(0,229,160,0.5);
}
@keyframes spinRing{from{transform:rotate(0deg);}to{transform:rotate(360deg);}}

.eyebrow{
  font-size:10px;letter-spacing:5px;color:var(--gold);
  text-transform:uppercase;margin-bottom:6px;font-weight:700;
  opacity:0;animation:fadeUp 0.6s 0.1s ease both;
}

.hero-name{
  font-family:'Bebas Neue',sans-serif;
  font-size:clamp(36px,11vw,52px);
  line-height:1;letter-spacing:3px;color:#fff;
  margin-bottom:4px;
  opacity:0;animation:fadeUp 0.6s 0.2s ease both;
}
.hero-name em{
  font-style:normal;
  background:linear-gradient(90deg,var(--gold),var(--gold2),var(--gold));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;
  background-size:200%;animation:goldShimmer 3s linear infinite;
}
@keyframes goldShimmer{0%{background-position:0%;}100%{background-position:200%;}}

.hero-sub{
  font-size:12px;color:var(--muted);font-weight:500;letter-spacing:1px;
  margin-bottom:20px;
  opacity:0;animation:fadeUp 0.6s 0.3s ease both;
}

/* Chart SVG */
.chart-svg{
  width:100%;height:55px;margin-bottom:24px;
  opacity:0;animation:fadeUp 0.6s 0.35s ease both;
}

/* ── VALUE PILLS ROW ── */
.pills{
  display:flex;gap:8px;justify-content:center;flex-wrap:wrap;
  margin-bottom:28px;
  opacity:0;animation:fadeUp 0.6s 0.4s ease both;
}
.pill{
  display:flex;align-items:center;gap:5px;
  padding:7px 14px;border-radius:100px;
  font-size:11px;font-weight:700;letter-spacing:0.5px;
}
.pill-g{background:rgba(0,229,160,0.08);border:1px solid rgba(0,229,160,0.2);color:var(--green);}
.pill-y{background:rgba(245,197,24,0.08);border:1px solid rgba(245,197,24,0.2);color:var(--gold2);}
.pill-p{background:rgba(123,97,255,0.08);border:1px solid rgba(123,97,255,0.2);color:#B4A0FF;}

/* ── URGENCY BANNER ── */
.urgency{
  background:linear-gradient(135deg,rgba(245,197,24,0.08),rgba(0,229,160,0.05));
  border:1px solid rgba(245,197,24,0.2);
  border-radius:14px;padding:14px 18px;
  margin-bottom:22px;
  display:flex;align-items:center;gap:12px;
  opacity:0;animation:fadeUp 0.6s 0.45s ease both;
}
.urgency-icon{font-size:22px;flex-shrink:0;}
.urgency-text{font-size:12px;color:var(--text);line-height:1.6;}
.urgency-text strong{color:var(--gold2);}

/* ── HINDI TEXT ── */
.hindi-cta{
  font-size:16px;font-weight:600;
  color:#c8d6e5;
  margin-bottom:16px;line-height:1.7;
  opacity:0;animation:fadeUp 0.6s 0.5s ease both;
}
.hindi-cta strong{
  color:var(--gold2);
  text-shadow:0 0 20px rgba(245,197,24,0.4);
}

/* ══════════════════════════════════
   MEGA 3D BUTTON
══════════════════════════════════ */
.btn-scene{
  perspective:800px;
  margin-bottom:14px;
  opacity:0;animation:fadeUp 0.7s 0.55s ease both;
}

.join-btn{
  display:block;width:100%;
  border:none;cursor:pointer;
  background:none;padding:0;
  border-radius:20px;
  transform-style:preserve-3d;
  transition:transform 0.12s ease;
  position:relative;
}

/* Outer glow rings */
.btn-glow{
  position:absolute;inset:-3px;border-radius:22px;
  background:linear-gradient(90deg,var(--gold),var(--green),var(--gold2),var(--gold));
  background-size:300%;
  animation:borderSpin 3s linear infinite;
  z-index:0;opacity:0.7;
}
@keyframes borderSpin{0%{background-position:0%;}100%{background-position:300%;}}

.btn-glow2{
  position:absolute;inset:-8px;border-radius:26px;
  background:linear-gradient(90deg,var(--gold),var(--green),var(--gold));
  background-size:200%;filter:blur(12px);opacity:0.35;
  animation:borderSpin 3s linear infinite reverse;z-index:0;
}

/* 3D depth */
.btn-depth{
  position:absolute;inset:3px;border-radius:18px;
  background:linear-gradient(180deg,#6b4400,#2e1c00);
  transform:translateZ(-10px) translateY(10px);
  filter:blur(4px);z-index:1;
}

/* Main face */
.btn-face{
  position:relative;z-index:2;
  border-radius:18px;padding:22px 24px;
  background:linear-gradient(160deg,#FFE066 0%,#F5C518 45%,#C98000 85%,#A06B00 100%);
  box-shadow:
    0 8px 0 #6b4000,
    0 14px 40px rgba(245,197,24,0.55),
    0 0 80px rgba(245,197,24,0.2),
    inset 0 1px 0 rgba(255,255,255,0.4),
    inset 0 -1px 0 rgba(0,0,0,0.2);
  display:flex;align-items:center;justify-content:center;gap:12px;
  overflow:hidden;
  transition:all 0.12s ease;
}

/* Shine sweep */
.btn-face::before{
  content:'';position:absolute;top:0;left:-80%;width:55%;height:100%;
  background:linear-gradient(90deg,transparent,rgba(255,255,255,0.4),transparent);
  transform:skewX(-15deg);
  animation:btnShine 2.5s ease-in-out infinite;
}
@keyframes btnShine{0%{left:-80%;}55%{left:130%;}100%{left:130%;}}

/* Outer pulse ring animation */
.btn-face::after{
  content:'';position:absolute;inset:0;border-radius:18px;
  animation:megaPulse 1.8s ease-out infinite;
}
@keyframes megaPulse{
  0%{box-shadow:0 0 0 0 rgba(245,197,24,0.7);}
  70%{box-shadow:0 0 0 20px rgba(245,197,24,0);}
  100%{box-shadow:0 0 0 0 rgba(245,197,24,0);}
}

.btn-tg{font-size:26px;line-height:1;filter:drop-shadow(0 2px 6px rgba(0,0,0,0.4));}
.btn-label{
  display:flex;flex-direction:column;align-items:flex-start;gap:1px;
}
.btn-main{
  font-family:'Bebas Neue',sans-serif;
  font-size:23px;letter-spacing:2.5px;color:#000;
  text-shadow:0 1px 0 rgba(255,255,255,0.3);line-height:1;
}
.btn-sub{
  font-size:10px;font-weight:700;letter-spacing:2px;
  color:rgba(0,0,0,0.55);text-transform:uppercase;
}

/* Hover */
.join-btn:hover .btn-face{
  transform:translateY(-4px);
  box-shadow:
    0 12px 0 #6b4000,
    0 20px 50px rgba(245,197,24,0.7),
    0 0 100px rgba(245,197,24,0.3),
    inset 0 1px 0 rgba(255,255,255,0.4);
}
/* Press */
.join-btn:active .btn-face{
  transform:translateY(6px);
  box-shadow:0 2px 0 #6b4000,0 4px 15px rgba(245,197,24,0.3);
}
.join-btn:active{transform:translateY(5px);}

/* Free label */
.free-row{
  display:flex;align-items:center;justify-content:center;gap:8px;
  margin-bottom:32px;
  opacity:0;animation:fadeUp 0.6s 0.65s ease both;
}
.free-tag{
  display:inline-flex;align-items:center;gap:5px;
  padding:6px 16px;border-radius:100px;
  background:rgba(0,229,160,0.07);
  border:1px solid rgba(0,229,160,0.2);
  font-size:11px;font-weight:700;color:var(--green);
  letter-spacing:0.5px;
}

/* ── SECTION ── */
.sec-title{
  font-size:10px;letter-spacing:4px;color:var(--gold);
  text-transform:uppercase;text-align:center;
  margin-bottom:16px;font-weight:700;
}

/* ── FEATURE GRID ── */
.feat-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:28px;}
.feat-card{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:16px;padding:18px 14px;
  transition:all 0.25s ease;
  position:relative;overflow:hidden;
}
.feat-card::before{
  content:'';position:absolute;top:0;left:0;right:0;height:2px;
  opacity:0;transition:opacity 0.3s;
}
.feat-card:nth-child(1)::before{background:linear-gradient(90deg,var(--gold),var(--gold2));}
.feat-card:nth-child(2)::before{background:linear-gradient(90deg,#7B61FF,#B4A0FF);}
.feat-card:nth-child(3)::before{background:linear-gradient(90deg,var(--green),#00b87a);}
.feat-card:nth-child(4)::before{background:linear-gradient(90deg,var(--red),#ff8c00);}
.feat-card:hover{transform:translateY(-4px);border-color:rgba(245,197,24,0.3);}
.feat-card:hover::before{opacity:1;}
.fi{font-size:28px;margin-bottom:10px;display:block;}
.fn{font-size:13px;font-weight:700;color:var(--text);margin-bottom:4px;}
.fd{font-size:11px;color:var(--muted);line-height:1.5;}

/* ── TAGS ── */
.tags{display:flex;flex-wrap:wrap;gap:7px;justify-content:center;margin-bottom:32px;}
.tag{
  padding:5px 12px;border-radius:100px;
  background:rgba(245,197,24,0.05);
  border:1px solid rgba(245,197,24,0.15);
  font-size:11px;color:var(--gold2);font-weight:600;
  transition:all 0.2s;cursor:default;
}
.tag:hover{background:rgba(245,197,24,0.1);border-color:rgba(245,197,24,0.3);}

/* ── DIVIDER ── */
.div{display:flex;align-items:center;gap:10px;margin:28px 0;}
.div-l{flex:1;height:1px;background:linear-gradient(90deg,transparent,var(--border),transparent);}
.div-d{color:var(--gold);font-size:10px;letter-spacing:3px;}

/* ── DISCLAIMER ── */
.disc{
  margin-top:24px;padding:16px;
  background:rgba(255,255,255,0.015);
  border:1px solid rgba(255,255,255,0.05);
  border-radius:12px;
  font-size:10px;color:var(--muted);
  line-height:1.8;text-align:center;
}

/* ANIMATIONS */
@keyframes fadeUp{
  from{opacity:0;transform:translateY(20px);}
  to{opacity:1;transform:translateY(0);}
}
</style>
</head>
<body>

<div class="bg-layer bg-grid"></div>
<div class="bg-layer bg-radial"></div>
<div class="orb orb1"></div>
<div class="orb orb2"></div>
<div class="orb orb3"></div>
<div class="scanline"></div>
<div class="particles" id="pts"></div>

<!-- TICKER -->
<div class="ticker-wrap">
  <div class="ticker-track">
    <div class="ti">NIFTY 50 <span class="up">▲ 0.62%</span></div>
    <div class="ti">SENSEX <span class="up">▲ 0.54%</span></div>
    <div class="ti">BANK NIFTY <span class="up">▲ 1.12%</span></div>
    <div class="ti">USDINR <span class="dn">▼ 0.18%</span></div>
    <div class="ti">MIDCAP 100 <span class="up">▲ 0.87%</span></div>
    <div class="ti">CRUDE OIL <span class="dn">▼ 0.43%</span></div>
    <div class="ti">IT INDEX <span class="up">▲ 1.35%</span></div>
    <div class="ti">GOLD <span class="up">▲ 0.29%</span></div>
    <div class="ti">NIFTY 50 <span class="up">▲ 0.62%</span></div>
    <div class="ti">SENSEX <span class="up">▲ 0.54%</span></div>
    <div class="ti">BANK NIFTY <span class="up">▲ 1.12%</span></div>
    <div class="ti">USDINR <span class="dn">▼ 0.18%</span></div>
    <div class="ti">MIDCAP 100 <span class="up">▲ 0.87%</span></div>
    <div class="ti">CRUDE OIL <span class="dn">▼ 0.43%</span></div>
    <div class="ti">IT INDEX <span class="up">▲ 1.35%</span></div>
    <div class="ti">GOLD <span class="up">▲ 0.29%</span></div>
  </div>
</div>

<div class="wrap">

  <!-- LIVE INDICATOR -->
  <div class="top-strip">
    <div class="live-dot"></div>
    <span class="live-text">Channel Live & Active</span>
  </div>

  <!-- HERO -->
  <div class="hero">
    <div class="av-wrap">
      <div class="av-ring"></div>
      <div class="av-mask"></div>
      <div class="av-inner">📈</div>
      <div class="av-badge">✓</div>
    </div>

    <p class="eyebrow">Official Telegram Channel</p>
    <h1 class="hero-name">TRADE WITH<br><em>PRATEEL SAHNI</em></h1>
    <p class="hero-sub">Stock Market Analysis &nbsp;•&nbsp; Indian Markets</p>

    <!-- Chart -->
    <svg class="chart-svg" viewBox="0 0 440 55" fill="none">
      <polyline points="0,48 44,40 88,44 132,26 176,30 220,14 264,18 308,8 352,12 396,4 440,7"
        stroke="url(#cg)" stroke-width="2.5" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
      <polyline points="0,48 44,40 88,44 132,26 176,30 220,14 264,18 308,8 352,12 396,4 440,7 440,55 0,55"
        fill="url(#ag)"/>
      <circle cx="440" cy="7" r="4" fill="var(--green)">
        <animate attributeName="r" values="4;7;4" dur="1.5s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="1;0.5;1" dur="1.5s" repeatCount="indefinite"/>
      </circle>
      <defs>
        <linearGradient id="cg" x1="0" y1="0" x2="440" y2="0">
          <stop offset="0%" stop-color="#F5C518"/>
          <stop offset="100%" stop-color="#00E5A0"/>
        </linearGradient>
        <linearGradient id="ag" x1="0" y1="0" x2="0" y2="55">
          <stop offset="0%" stop-color="#00E5A0" stop-opacity="0.2"/>
          <stop offset="100%" stop-color="#00E5A0" stop-opacity="0"/>
        </linearGradient>
      </defs>
    </svg>

    <!-- Value pills -->
    <div class="pills">
      <div class="pill pill-g">📊 Daily Analysis</div>
      <div class="pill pill-y">🎓 Free Education</div>
      <div class="pill pill-p">📰 Market News</div>
    </div>

    <!-- Urgency banner -->
    <div class="urgency">
      <span class="urgency-icon">🔥</span>
      <div class="urgency-text">
        Stock market seekhna ho ya market ko samajhna ho —<br>
        <strong>yeh channel aapke liye bilkul free hai.</strong>
      </div>
    </div>

    <!-- Hindi CTA text -->
    <p class="hindi-cta">
      👇 Abhi Join Karo — <strong>Bilkul Free!</strong> 👇
    </p>

    <!-- ★ MEGA BUTTON ★ -->
    <div class="btn-scene">
      <button class="join-btn" onclick="joinChannel()">
        <div class="btn-glow2"></div>
        <div class="btn-glow"></div>
        <div class="btn-depth"></div>
        <div class="btn-face">
          <span class="btn-tg">✈️</span>
          <div class="btn-label">
            <span class="btn-main">JOIN TELEGRAM CHANNEL</span>
            <span class="btn-sub">Tap karo &amp; channel join karo</span>
          </div>
        </div>
      </button>
    </div>

    <div class="free-row">
      <div class="free-tag">✓ &nbsp;Free to Join &nbsp;•&nbsp; No Charges</div>
    </div>
  </div>

  <div class="div"><div class="div-l"></div><span class="div-d">◆ ◆ ◆</span><div class="div-l"></div></div>

  <!-- FEATURES -->
  <p class="sec-title">Is Channel Mein Milega</p>
  <div class="feat-grid">
    <div class="feat-card">
      <span class="fi">📊</span>
      <div class="fn">Market Analysis</div>
      <div class="fd">Nifty, Sensex aur Sectoral Index ka daily breakdown</div>
    </div>
    <div class="feat-card">
      <span class="fi">🧠</span>
      <div class="fn">Chart Reading</div>
      <div class="fd">Technical patterns aur indicators clearly samjho</div>
    </div>
    <div class="feat-card">
      <span class="fi">📰</span>
      <div class="fn">Market News</div>
      <div class="fd">Important financial news jo market ko affect kare</div>
    </div>
    <div class="feat-card">
      <span class="fi">🎓</span>
      <div class="fn">Education</div>
      <div class="fd">Beginners se advance tak simple bhasha mein</div>
    </div>
  </div>

  <!-- TOPICS -->
  <p class="sec-title">Topics Covered</p>
  <div class="tags">
    <span class="tag">Equity</span>
    <span class="tag">Options Basics</span>
    <span class="tag">Futures</span>
    <span class="tag">IPO</span>
    <span class="tag">Swing Trading</span>
    <span class="tag">Risk Management</span>
    <span class="tag">Macro Economy</span>
    <span class="tag">Sector Rotation</span>
  </div>

  <div class="disc">
    ⚠️ <strong>Disclaimer:</strong> Yeh channel sirf educational aur informational purpose ke liye hai.
    Yahan share ki gayi koi bhi content financial advice nahi hai.
    Invest karne se pehle apne financial advisor se zar
