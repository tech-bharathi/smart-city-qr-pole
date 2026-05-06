<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Smart City QR Pole · Satellite Command · Chittoor</title>
  <meta name="description" content="Smart City QR Pole – satellite-connected live tracking system with all-India routes, hospitals, emergency and more">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css">
  <style>
    /* ── CSS Variables & base reset ── */
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    :root {
      --font-sans: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      --border-radius-lg: 12px;
      --border-radius-md: 8px;
      --color-background-primary: #ffffff;
      --color-background-secondary: #f5f5f5;
      --color-background-info: #dbeafe;
      --color-background-success: #dcfce7;
      --color-background-warning: #fef9c3;
      --color-background-danger: #fee2e2;
      --color-border-secondary: #d1d5db;
      --color-border-tertiary: #e5e7eb;
      --color-text-primary: #111827;
      --color-text-secondary: #6b7280;
      --color-text-info: #1d4ed8;
      --color-text-success: #15803d;
      --color-text-warning: #a16207;
      --color-text-danger: #b91c1c;
    }
    body {
      font-family: var(--font-sans);
      background: #f0f4f8;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      padding: 1rem;
    }
    /* Form element styling (missing in original) */
    .complaint-form select,
    .complaint-form textarea,
    .complaint-form input {
      padding: 6px 10px;
      border: 0.5px solid var(--color-border-secondary);
      border-radius: var(--border-radius-md);
      font-family: var(--font-sans);
    }
    .sub-btn:hover { background: #1a6bbf; }
    /* Screenreader only */
    .sr-only { position:absolute; width:1px; height:1px; padding:0; margin:-1px; overflow:hidden; clip:rect(0,0,0,0); white-space:nowrap; border:0; }
  </style>
</head>
<body>

<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:var(--font-sans)}
.app{padding:1rem 0;max-width:680px}
.hdr{background:#050e1f;border-radius:var(--border-radius-lg);padding:1.25rem;margin-bottom:10px}
.hdr-top{display:flex;align-items:center;gap:12px;margin-bottom:10px}
.sat-ring{width:48px;height:48px;border-radius:50%;border:2px solid #378ADD;display:flex;align-items:center;justify-content:center;flex-shrink:0;position:relative}
.sat-ring::after{content:'';position:absolute;width:60px;height:60px;border-radius:50%;border:1px solid rgba(55,138,221,0.3)}
.sat-ring i{font-size:20px;color:#85B7EB}
.hdr h1{font-size:17px;font-weight:500;color:#fff}
.hdr p{font-size:11px;color:rgba(255,255,255,0.5);margin-top:2px}
.sat-status{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:10px}
.sstat{display:flex;align-items:center;gap:5px;font-size:11px;color:rgba(255,255,255,0.6)}
.sstat-dot{width:6px;height:6px;border-radius:50%}
.pulse{animation:pulse 1.5s infinite}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:0.3}}
.lang-row{display:flex;gap:5px;flex-wrap:wrap}
.lb{padding:3px 9px;border-radius:20px;border:1px solid rgba(255,255,255,0.25);background:rgba(255,255,255,0.08);color:rgba(255,255,255,0.8);font-size:11px;cursor:pointer}
.lb.on{background:#378ADD;color:#fff;border-color:#378ADD}
.nav{display:flex;gap:5px;flex-wrap:wrap;margin-bottom:10px}
.nb{padding:6px 11px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);background:var(--color-background-primary);font-size:11px;color:var(--color-text-secondary);cursor:pointer;display:flex;align-items:center;gap:4px}
.nb.on{background:#185FA5;color:#fff;border-color:#185FA5}
.nb i{font-size:12px}
.panel{display:none}
.panel.on{display:block}
.card{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1rem;margin-bottom:10px}
.ct{font-size:11px;color:var(--color-text-secondary);text-transform:uppercase;letter-spacing:0.5px;margin-bottom:10px;display:flex;align-items:center;gap:6px}
.ct i{font-size:14px}
.g2{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:8px;margin-bottom:10px}
.g3{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:8px;margin-bottom:10px}
.g4{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:8px;margin-bottom:10px}
.stat{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:10px 12px}
.sl{font-size:11px;color:var(--color-text-secondary);margin-bottom:3px}
.sv{font-size:20px;font-weight:500;color:var(--color-text-primary)}
.su{font-size:11px;color:var(--color-text-secondary)}
.row{display:flex;align-items:center;padding:7px 0;border-bottom:0.5px solid var(--color-border-tertiary)}
.row:last-child{border-bottom:none}
.badge{padding:2px 8px;border-radius:12px;font-size:11px;font-weight:500}
.bb{background:#B5D4F4;color:#042C53}
.gb{background:#C0DD97;color:#173404}
.rb{background:#F7C1C1;color:#501313}
.ab{background:#FAC775;color:#412402}
.tb{background:#9FE1CB;color:#04342C}
.pb{background:#CECBF6;color:#26215C}
.india-map{background:#e8f4f8;border-radius:var(--border-radius-lg);overflow:hidden;position:relative;margin-bottom:10px}
.imap-svg{width:100%;height:360px}
.route-line{stroke-dasharray:6,3;animation:dash 2s linear infinite}
@keyframes dash{to{stroke-dashoffset:-18}}
.bus-dot{animation:moveBus 4s linear infinite}
.train-dot{animation:moveTrain 6s linear infinite}
.flight-dot{animation:moveFlight 3s linear infinite}
@keyframes moveBus{0%{offset-distance:0%}100%{offset-distance:100%}}
.map-ctrl{display:flex;gap:5px;padding:8px 10px;background:var(--color-background-secondary);border-top:0.5px solid var(--color-border-tertiary);flex-wrap:wrap}
.mc{padding:4px 10px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);background:var(--color-background-primary);font-size:11px;color:var(--color-text-secondary);cursor:pointer}
.mc.on{background:#185FA5;color:#fff;border-color:#185FA5}
.city-dot{cursor:pointer}
.city-dot circle{transition:r 0.2s}
.city-dot:hover circle{r:8}
.tooltip-box{background:#050e1f;color:#fff;font-size:11px;padding:6px 10px;border-radius:6px;pointer-events:none}
.live-ticker{background:#050e1f;border-radius:var(--border-radius-md);padding:8px 12px;margin-bottom:10px;overflow:hidden}
.ticker-inner{display:flex;gap:30px;animation:ticker 20s linear infinite;white-space:nowrap}
@keyframes ticker{0%{transform:translateX(0)}100%{transform:translateX(-50%)}}
.ticker-item{font-size:11px;color:rgba(255,255,255,0.7);display:flex;align-items:center;gap:6px;flex-shrink:0}
.ticker-dot{width:6px;height:6px;border-radius:50%;flex-shrink:0}
.bus-card{border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:10px;margin-bottom:8px}
.bc-head{display:flex;align-items:center;gap:8px;margin-bottom:6px}
.bc-num{min-width:42px;height:26px;border-radius:var(--border-radius-md);display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:500;background:#185FA5;color:#fff}
.bc-name{font-size:13px;font-weight:500;color:var(--color-text-primary);flex:1}
.prog{height:5px;background:var(--color-background-secondary);border-radius:3px;overflow:hidden;margin:5px 0}
.prog-f{height:100%;border-radius:3px}
.bc-meta{display:flex;gap:10px;flex-wrap:wrap}
.bc-m{font-size:11px;color:var(--color-text-secondary);display:flex;align-items:center;gap:3px}
.bc-m i{font-size:12px}
.sat-panel{background:#050e1f;border-radius:var(--border-radius-lg);padding:1rem;margin-bottom:10px}
.sat-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:10px}
.sat-card{background:rgba(55,138,221,0.1);border:0.5px solid rgba(55,138,221,0.3);border-radius:var(--border-radius-md);padding:8px}
.sat-label{font-size:10px;color:rgba(255,255,255,0.5);margin-bottom:3px}
.sat-val{font-size:16px;font-weight:500;color:#85B7EB}
.sat-sub{font-size:10px;color:rgba(255,255,255,0.4)}
.sat-orbit{position:relative;width:140px;height:140px;margin:0 auto 10px}
.orbit-earth{width:40px;height:40px;border-radius:50%;background:#1D9E75;border:2px solid #5DCAA5;position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);display:flex;align-items:center;justify-content:center;font-size:18px}
.orbit-ring{position:absolute;border-radius:50%;border:1px solid rgba(55,138,221,0.3);top:50%;left:50%;transform:translate(-50%,-50%)}
.orbit-sat{position:absolute;width:14px;height:14px;border-radius:50%;background:#378ADD;top:50%;left:50%;font-size:8px;display:flex;align-items:center;justify-content:center;color:#fff}
.qr-connect{background:#050e1f;border-radius:var(--border-radius-lg);padding:1rem;margin-bottom:10px;display:flex;gap:14px;align-items:center}
.qr-svg-w{width:56px;height:56px;flex-shrink:0}
.qr-info h3{font-size:13px;font-weight:500;color:#fff;margin-bottom:4px}
.qr-info p{font-size:11px;color:rgba(255,255,255,0.5);line-height:1.6}
.signal-bars{display:flex;align-items:flex-end;gap:2px;height:16px}
.signal-bars span{width:4px;border-radius:1px;background:#378ADD}
.hosp-card{border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:10px;margin-bottom:8px}
.hc-head{display:flex;align-items:center;gap:8px;margin-bottom:6px}
.hc-av{width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:500;flex-shrink:0}
.hc-name{font-size:13px;font-weight:500;color:var(--color-text-primary)}
.hc-dist{font-size:11px;color:var(--color-text-secondary)}
.hc-tags{display:flex;gap:4px;flex-wrap:wrap;margin-bottom:6px}
.hc-tag{font-size:10px;padding:2px 6px;border-radius:8px;background:var(--color-background-info);color:var(--color-text-info)}
.hc-row{display:flex;justify-content:space-between;font-size:12px;padding:2px 0;color:var(--color-text-secondary)}
.hc-row span:last-child{color:var(--color-text-primary)}
.emer-strip{background:#FCEBEB;border:0.5px solid #F7C1C1;border-radius:var(--border-radius-md);padding:10px 14px;margin-bottom:10px}
.emer-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
.emer-item{text-align:center}
.emer-num{font-size:20px;font-weight:500;color:#501313}
.emer-lbl{font-size:10px;color:#A32D2D}
.ann-item{padding:8px 0;border-bottom:0.5px solid var(--color-border-tertiary)}
.ann-item:last-child{border-bottom:none}
.ann-tag{display:inline-block;font-size:10px;padding:2px 7px;border-radius:10px;margin-bottom:3px;background:var(--color-background-info);color:var(--color-text-info)}
.ann-text{font-size:13px;color:var(--color-text-primary);line-height:1.5}
.ann-date{font-size:10px;color:var(--color-text-secondary);margin-top:2px}
.complaint-form{display:flex;flex-direction:column;gap:10px}
.complaint-form select,.complaint-form textarea,.complaint-form input{width:100%;font-size:13px}
.complaint-form textarea{height:80px;resize:vertical}
.sub-btn{padding:8px 18px;background:#185FA5;color:#fff;border:none;border-radius:var(--border-radius-md);font-size:13px;cursor:pointer;font-weight:500}
.smsg{background:#EAF3DE;border:0.5px solid #C0DD97;border-radius:var(--border-radius-md);padding:10px 14px;font-size:13px;color:#173404;display:none}
.weather-big{font-size:40px;font-weight:500;color:var(--color-text-primary)}
.prog-bar2{height:6px;background:linear-gradient(to right,#C0DD97,#FAC775,#F09595,#E24B4A);border-radius:3px;position:relative;margin:6px 0}
.prog-marker{position:absolute;top:-5px;width:14px;height:14px;border-radius:50%;background:var(--color-background-primary);border:2px solid #BA7517}
.wifi-z{background:#E1F5EE;border:0.5px solid #5DCAA5;border-radius:var(--border-radius-md);padding:10px 14px;display:flex;align-items:center;gap:10px;margin-bottom:8px}
.wifi-z i{font-size:18px;color:#0F6E56}
.wifi-name{font-size:13px;font-weight:500;color:#04342C}
.wifi-info{font-size:11px;color:#085041}
.tour-c{border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:10px;margin-bottom:8px;display:flex;gap:10px}
.tour-ic{width:36px;height:36px;border-radius:var(--border-radius-md);display:flex;align-items:center;justify-content:center;font-size:16px;flex-shrink:0}
.tour-name{font-size:13px;font-weight:500;color:var(--color-text-primary)}
.tour-desc{font-size:11px;color:var(--color-text-secondary);line-height:1.5;margin-top:2px}
.tour-tags{display:flex;gap:5px;margin-top:5px;flex-wrap:wrap}
.tour-tag{font-size:10px;padding:2px 6px;border-radius:8px;background:var(--color-background-secondary);color:var(--color-text-secondary)}
</style>

<div class="app">
<h2 class="sr-only">Smart City QR Pole – satellite-connected live tracking system with all-India routes, hospitals, emergency and more</h2>

<div class="hdr">
  <div class="hdr-top">
    <div class="sat-ring"><i class="ti ti-antenna" aria-hidden="true"></i></div>
    <div>
      <h1 id="ht">Smart City QR Pole · Satellite Command</h1>
      <p id="hs">ISRO NavIC + GPS · Connected · All India Coverage · Pole ID: CIT-QR-0042</p>
    </div>
  </div>
  <div class="sat-status">
    <div class="sstat"><div class="sstat-dot pulse" style="background:#639922"></div><span id="ss1">NavIC satellite: LIVE</span></div>
    <div class="sstat"><div class="sstat-dot pulse" style="background:#378ADD"></div><span id="ss2">GPS lock: 12 sats</span></div>
    <div class="sstat"><div class="sstat-dot pulse" style="background:#EF9F27"></div><span id="ss3">Signal: 98.4%</span></div>
    <div class="sstat"><div class="sstat-dot" style="background:#5DCAA5"></div><span id="ss4">Last sync: 2s ago</span></div>
  </div>
  <div class="lang-row">
    <button class="lb on" onclick="setL('en',this)">🇬🇧 EN</button>
    <button class="lb" onclick="setL('hi',this)">🇮🇳 HI</button>
    <button class="lb" onclick="setL('te',this)">🏵 TE</button>
    <button class="lb" onclick="setL('ta',this)">🌺 TA</button>
    <button class="lb" onclick="setL('bn',this)">🐟 BN</button>
    <button class="lb" onclick="setL('mr',this)">🦋 MR</button>
    <button class="lb" onclick="setL('fr',this)">🇫🇷 FR</button>
    <button class="lb" onclick="setL('de',this)">🇩🇪 DE</button>
    <button class="lb" onclick="setL('zh',this)">🇨🇳 ZH</button>
    <button class="lb" onclick="setL('ja',this)">🇯🇵 JP</button>
    <button class="lb" onclick="setL('ar',this)">🇸🇦 AR</button>
  </div>
</div>

<div class="live-ticker" id="ticker">
  <div class="ticker-inner" id="tickerInner"></div>
</div>

<div class="nav">
  <button class="nb on" onclick="showP('map',this)"><i class="ti ti-map-2" aria-hidden="true"></i><span id="n1">India Map</span></button>
  <button class="nb" onclick="showP('bus',this)"><i class="ti ti-bus" aria-hidden="true"></i><span id="n2">Bus Track</span></button>
  <button class="nb" onclick="showP('train',this)"><i class="ti ti-train" aria-hidden="true"></i><span id="n3">Trains</span></button>
  <button class="nb" onclick="showP('hospital',this)"><i class="ti ti-building-hospital" aria-hidden="true"></i><span id="n4">Hospitals</span></button>
  <button class="nb" onclick="showP('emergency',this)"><i class="ti ti-phone-call" aria-hidden="true"></i><span id="n5">Emergency</span></button>
  <button class="nb" onclick="showP('satellite',this)"><i class="ti ti-antenna" aria-hidden="true"></i><span id="n6">Satellite</span></button>
  <button class="nb" onclick="showP('weather',this)"><i class="ti ti-cloud" aria-hidden="true"></i><span id="n7">Weather</span></button>
  <button class="nb" onclick="showP('tourism',this)"><i class="ti ti-camera" aria-hidden="true"></i><span id="n8">Tourism</span></button>
  <button class="nb" onclick="showP('wifi',this)"><i class="ti ti-wifi" aria-hidden="true"></i><span id="n9">Wi-Fi</span></button>
  <button class="nb" onclick="showP('announce',this)"><i class="ti ti-speakerphone" aria-hidden="true"></i><span id="n10">Alerts</span></button>
  <button class="nb" onclick="showP('complaint',this)"><i class="ti ti-message-circle" aria-hidden="true"></i><span id="n11">Complaint</span></button>
</div>

<div id="p-map" class="panel on">
  <div class="india-map">
    <svg class="imap-svg" viewBox="0 0 500 380" xmlns="http://www.w3.org/2000/svg" id="indiasvg">
      <rect width="500" height="380" fill="#d4e8f5"/>
      <polygon points="120,30 160,20 200,25 240,18 280,22 310,15 340,28 360,45 370,70 380,95 385,120 375,145 360,165 340,180 320,195 300,210 280,230 270,255 265,275 260,295 255,310 250,325 240,340 230,355 220,365 215,370 210,365 205,355 195,340 185,325 178,310 172,295 165,275 158,255 150,235 140,215 125,195 110,175 95,155 82,135 75,115 72,90 78,65 95,45 120,30" fill="#c8e0b0" stroke="#8ab870" stroke-width="1.5"/>
      <polygon points="340,28 360,45 370,70 380,95 385,120 370,125 355,115 340,100 320,90 300,80 285,70 280,55 290,40 310,30" fill="#b8d8a0" stroke="#8ab870" stroke-width="1"/>
      <polygon points="120,30 100,40 80,50 72,70 78,65 95,45" fill="#c0daa8" stroke="#8ab870" stroke-width="1"/>
      <line x1="215" y1="370" x2="210" y2="340" stroke="#9fc87f" stroke-width="8" stroke-linecap="round"/>
      <line x1="210" y1="340" x2="195" y2="310" stroke="#9fc87f" stroke-width="6" stroke-linecap="round"/>

      <text x="130" y="75" font-size="9" fill="#2C2C2A" font-weight="500">Delhi</text>
      <text x="290" y="110" font-size="9" fill="#2C2C2A" font-weight="500">Kolkata</text>
      <text x="180" y="200" font-size="9" fill="#2C2C2A" font-weight="500">Mumbai</text>
      <text x="270" y="210" font-size="9" fill="#2C2C2A" font-weight="500">Hyderabad</text>
      <text x="260" y="265" font-size="9" fill="#2C2C2A" font-weight="500">Bengaluru</text>
      <text x="285" y="300" font-size="9" fill="#2C2C2A" font-weight="500">Chennai</text>
      <text x="145" y="115" font-size="9" fill="#2C2C2A" font-weight="500">Jaipur</text>
      <text x="195" y="150" font-size="9" fill="#2C2C2A" font-weight="500">Bhopal</text>
      <text x="340" y="75" font-size="9" fill="#2C2C2A" font-weight="500">Guwahati</text>
      <text x="244" y="292" font-size="9" fill="#042C53" font-weight="500">Chittoor</text>

      <g id="layer-bus">
        <line x1="138" y1="72" x2="300" y2="105" stroke="#185FA5" stroke-width="1.5" stroke-dasharray="5,3" class="route-line"/>
        <line x1="138" y1="72" x2="185" y2="195" stroke="#185FA5" stroke-width="1.5" stroke-dasharray="5,3" class="route-line"/>
        <line x1="185" y1="195" x2="280" y2="205" stroke="#185FA5" stroke-width="1.5" stroke-dasharray="5,3" class="route-line"/>
        <line x1="280" y1="205" x2="270" y2="260" stroke="#185FA5" stroke-width="1.5" stroke-dasharray="5,3" class="route-line"/>
        <line x1="270" y1="260" x2="290" y2="295" stroke="#185FA5" stroke-width="1.5" stroke-dasharray="5,3" class="route-line"/>
        <line x1="290" y1="295" x2="255" y2="285" stroke="#185FA5" stroke-width="1.5" stroke-dasharray="5,3" class="route-line"/>
        <line x1="255" y1="285" x2="245" y2="305" stroke="#4a90d9" stroke-width="2" stroke-dasharray="4,2" class="route-line"/>
        <rect x="162" y="130" width="20" height="10" rx="2" fill="#185FA5" id="busA"/>
        <rect x="225" y="200" width="20" height="10" rx="2" fill="#0F6E56" id="busB"/>
        <rect x="270" y="240" width="20" height="10" rx="2" fill="#993C1D" id="busC"/>
      </g>
      <g id="layer-train">
        <line x1="138" y1="72" x2="295" y2="108" stroke="#A32D2D" stroke-width="2" stroke-dasharray="8,4" class="route-line" style="display:none" id="tl1"/>
        <line x1="185" y1="195" x2="290" y2="295" stroke="#A32D2D" stroke-width="2" stroke-dasharray="8,4" class="route-line" style="display:none" id="tl2"/>
        <line x1="138" y1="72" x2="185" y2="195" stroke="#A32D2D" stroke-width="2" stroke-dasharray="8,4" class="route-line" style="display:none" id="tl3"/>
        <circle cx="200" cy="155" r="5" fill="#A32D2D" id="trainA" style="display:none"/>
        <circle cx="238" cy="243" r="5" fill="#A32D2D" id="trainB" style="display:none"/>
      </g>
      <g id="layer-flight">
        <line x1="138" y1="72" x2="290" y2="295" stroke="#534AB7" stroke-width="1" stroke-dasharray="3,3" class="route-line" style="display:none" id="fl1"/>
        <line x1="185" y1="195" x2="345" y2="70" stroke="#534AB7" stroke-width="1" stroke-dasharray="3,3" class="route-line" style="display:none" id="fl2"/>
        <circle cx="210" cy="180" r="4" fill="#534AB7" id="flightA" style="display:none"/>
        <circle cx="262" cy="133" r="4" fill="#534AB7" id="flightB" style="display:none"/>
      </g>

      <g class="city-dot" onclick="cityClick('Delhi')"><circle cx="138" cy="72" r="6" fill="#185FA5"/><text x="138" y="70" font-size="0" fill="none">Delhi</text></g>
      <g class="city-dot" onclick="cityClick('Kolkata')"><circle cx="300" cy="105" r="6" fill="#185FA5"/></g>
      <g class="city-dot" onclick="cityClick('Mumbai')"><circle cx="185" cy="195" r="6" fill="#185FA5"/></g>
      <g class="city-dot" onclick="cityClick('Hyderabad')"><circle cx="280" cy="205" r="6" fill="#185FA5"/></g>
      <g class="city-dot" onclick="cityClick('Bengaluru')"><circle cx="270" cy="260" r="6" fill="#185FA5"/></g>
      <g class="city-dot" onclick="cityClick('Chennai')"><circle cx="290" cy="295" r="6" fill="#185FA5"/></g>
      <g class="city-dot" onclick="cityClick('Jaipur')"><circle cx="150" cy="108" r="5" fill="#185FA5"/></g>
      <g class="city-dot" onclick="cityClick('Bhopal')"><circle cx="200" cy="148" r="5" fill="#185FA5"/></g>
      <g class="city-dot" onclick="cityClick('Guwahati')"><circle cx="345" cy="70" r="5" fill="#185FA5"/></g>
      <g class="city-dot" onclick="cityClick('Chittoor')"><circle cx="247" cy="285" r="7" fill="#A32D2D"/><circle cx="247" cy="285" r="11" fill="none" stroke="#A32D2D" stroke-width="1.5"/></g>

      <rect x="8" y="8" width="110" height="14" rx="3" fill="rgba(5,14,31,0.75)"/>
      <text x="12" y="18" font-size="8" fill="#85B7EB">NavIC Live · 12 satellites locked</text>

      <rect x="8" y="26" width="55" height="10" rx="2" fill="rgba(24,95,165,0.8)"/>
      <text x="12" y="33.5" font-size="7" fill="#fff">Bus routes</text>
      <rect x="67" y="26" width="55" height="10" rx="2" fill="rgba(163,45,45,0.8)"/>
      <text x="71" y="33.5" font-size="7" fill="#fff">Rail routes</text>
      <rect x="126" y="26" width="55" height="10" rx="2" fill="rgba(83,74,183,0.8)"/>
      <text x="130" y="33.5" font-size="7" fill="#fff">Flight paths</text>
    </svg>
    <div class="map-ctrl">
      <button class="mc on" onclick="toggleLayer('bus',this)"><i class="ti ti-bus" style="font-size:11px" aria-hidden="true"></i> Bus</button>
      <button class="mc" onclick="toggleLayer('train',this)"><i class="ti ti-train" style="font-size:11px" aria-hidden="true"></i> Train</button>
      <button class="mc" onclick="toggleLayer('flight',this)"><i class="ti ti-plane" style="font-size:11px" aria-hidden="true"></i> Flight</button>
      <span id="city-info" style="font-size:11px;color:var(--color-text-secondary);margin-left:auto;align-self:center">Click a city for live info</span>
    </div>
  </div>
  <div class="g4">
    <div class="stat"><div class="sl" id="ms1">Active buses</div><div class="sv" id="msv1">1,284</div></div>
    <div class="stat"><div class="sl" id="ms2">Active trains</div><div class="sv" id="msv2">312</div></div>
    <div class="stat"><div class="sl" id="ms3">QR poles</div><div class="sv" id="msv3">4,820</div></div>
    <div class="stat"><div class="sl" id="ms4">Cities covered</div><div class="sv" id="msv4">286</div></div>
  </div>
</div>

<div id="p-bus" class="panel">
  <div class="g3">
    <div class="stat"><div class="sl" id="bst1">Live routes</div><div class="sv">6</div></div>
    <div class="stat"><div class="sl" id="bst2">On time</div><div class="sv">83%</div></div>
    <div class="stat"><div class="sl" id="bst3">Avg occupancy</div><div class="sv">61%</div></div>
  </div>
  <div class="card">
    <div class="ct"><i class="ti ti-bus" aria-hidden="true"></i><span id="btt">Live Bus Tracking · Satellite GPS</span></div>
    <div style="margin-bottom:10px;font-size:12px;color:var(--color-text-secondary)"><span style="display:inline-block;width:7px;height:7px;border-radius:50%;background:#639922;animation:pulse 1.5s infinite;margin-right:5px"></span><span id="bls">ISRO NavIC feed · updates every 15s</span></div>
    <div id="busListEl"></div>
  </div>
</div>

<div id="p-train" class="panel">
  <div class="card">
    <div class="ct"><i class="ti ti-train" aria-hidden="true"></i><span id="trt">Live Train Status · All India</span></div>
    <div id="trainListEl"></div>
  </div>
  <div class="g3">
    <div class="stat"><div class="sl" id="tst1">Trains running</div><div class="sv">312</div></div>
    <div class="stat"><div class="sl" id="tst2">On schedule</div><div class="sv">74%</div></div>
    <div class="stat"><div class="sl" id="tst3">Delayed</div><div class="sv">26%</div></div>
  </div>
</div>

<div id="p-hospital" class="panel">
  <div class="g3">
    <div class="stat"><div class="sl" id="hst1">Total hospitals</div><div class="sv">6</div></div>
    <div class="stat"><div class="sl" id="hst2">Beds available</div><div class="sv">218</div></div>
    <div class="stat"><div class="sl" id="hst3">Ambulances</div><div class="sv">12</div></div>
  </div>
  <div class="card">
    <div class="ct"><i class="ti ti-building-hospital" aria-hidden="true"></i><span id="hpt">Nearby Hospitals · Live Bed Status</span></div>
    <div id="hospListEl"></div>
  </div>
</div>

<div id="p-emergency" class="panel">
  <div class="emer-strip">
    <div style="font-size:12px;font-weight:500;color:#501313;margin-bottom:8px" id="eht">Emergency Helplines · India</div>
    <div class="emer-grid">
      <div class="emer-item"><div class="emer-num">100</div><div class="emer-lbl" id="e1l">Police</div></div>
      <div class="emer-item"><div class="emer-num">108</div><div class="emer-lbl" id="e2l">Ambulance</div></div>
      <div class="emer-item"><div class="emer-num">101</div><div class="emer-lbl" id="e3l">Fire</div></div>
      <div class="emer-item"><div class="emer-num">1091</div><div class="emer-lbl" id="e4l">Women</div></div>
      <div class="emer-item"><div class="emer-num">1098</div><div class="emer-lbl" id="e5l">Child</div></div>
      <div class="emer-item"><div class="emer-num">1077</div><div class="emer-lbl" id="e6l">Disaster</div></div>
      <div class="emer-item"><div class="emer-num">102</div><div class="emer-lbl" id="e7l">Maternity</div></div>
      <div class="emer-item"><div class="emer-num">1800</div><div class="emer-lbl" id="e8l">Poison</div></div>
      <div class="emer-item"><div class="emer-num">112</div><div class="emer-lbl" id="e9l">All Emergencies</div></div>
    </div>
  </div>
  <div class="card">
    <div class="ct"><i class="ti ti-map-pin" aria-hidden="true"></i><span id="enl">Nearest Services · GPS Located</span></div>
    <div class="row"><div style="width:8px;height:8px;border-radius:50%;background:#A32D2D;margin-right:10px;flex-shrink:0"></div><div style="flex:1"><div style="font-size:13px;color:var(--color-text-primary)" id="es1">Chittoor Police Station</div><div style="font-size:11px;color:var(--color-text-secondary)">0.4 km · 24/7 · Ph: 08572-224433</div></div><span class="badge rb">Active</span></div>
    <div class="row"><div style="width:8px;height:8px;border-radius:50%;background:#A32D2D;margin-right:10px;flex-shrink:0"></div><div style="flex:1"><div style="font-size:13px;color:var(--color-text-primary)" id="es2">City Hospital Emergency</div><div style="font-size:11px;color:var(--color-text-secondary)">0.3 km · 24/7 · Ph: 08572-234567</div></div><span class="badge gb">Ready</span></div>
    <div class="row"><div style="width:8px;height:8px;border-radius:50%;background:#BA7517;margin-right:10px;flex-shrink:0"></div><div style="flex:1"><div style="font-size:13px;color:var(--color-text-primary)" id="es3">Fire & Rescue Station</div><div style="font-size:11px;color:var(--color-text-secondary)">1.2 km · 24/7</div></div><span class="badge gb">Ready</span></div>
    <div class="row"><div style="width:8px;height:8px;border-radius:50%;background:#534AB7;margin-right:10px;flex-shrink:0"></div><div style="flex:1"><div style="font-size:13px;color:var(--color-text-primary)" id="es4">108 Ambulance Hub</div><div style="font-size:11px;color:var(--color-text-secondary)">0.8 km · 2 units standby</div></div><span class="badge tb">Standby</span></div>
    <div class="row"><div style="width:8px;height:8px;border-radius:50%;background:#639922;margin-right:10px;flex-shrink:0"></div><div style="flex:1"><div style="font-size:13px;color:var(--color-text-primary)" id="es5">Traffic Control Point</div><div style="font-size:11px;color:var(--color-text-secondary)">0.2 km · CCTV monitored</div></div><span class="badge gb">Active</span></div>
  </div>
  <div class="card">
    <div class="ct"><i class="ti ti-first-aid-kit" aria-hidden="true"></i><span id="fat">First Aid · Satellite SOS</span></div>
    <div style="font-size:13px;color:var(--color-text-secondary);line-height:1.8" id="fad">SOS button on this pole alerts nearest emergency service via satellite · Stay calm · Call 112 · Do not move injured · CPR: 30 compressions + 2 breaths · Burns: cool water 10 min · Choking: back blows</div>
  </div>
</div>

<div id="p-satellite" class="panel">
  <div class="sat-panel">
    <div style="font-size:13px;font-weight:500;color:#85B7EB;margin-bottom:12px;display:flex;align-items:center;gap:8px"><i class="ti ti-antenna" style="font-size:16px" aria-hidden="true"></i><span id="satHead">Satellite Connection · ISRO NavIC</span></div>
    <div class="sat-orbit">
      <div class="orbit-ring" style="width:60px;height:60px"></div>
      <div class="orbit-ring" style="width:90px;height:90px"></div>
      <div class="orbit-ring" style="width:120px;height:120px"></div>
      <div class="orbit-earth">🌏</div>
      <div class="orbit-sat" id="os1" style="transform:translate(-50%,-50%) rotate(0deg) translateX(30px) rotate(0deg)">S</div>
      <div class="orbit-sat" id="os2" style="transform:translate(-50%,-50%) rotate(120deg) translateX(45px) rotate(-120deg)">S</div>
      <div class="orbit-sat" id="os3" style="transform:translate(-50%,-50%) rotate(240deg) translateX(45px) rotate(-240deg)">S</div>
      <div class="orbit-sat" id="os4" style="transform:translate(-50%,-50%) rotate(60deg) translateX(58px) rotate(-60deg)">S</div>
    </div>
    <div class="sat-grid">
      <div class="sat-card"><div class="sat-label" id="sl1">Satellites locked</div><div class="sat-val">12</div><div class="sat-sub">NavIC + GPS</div></div>
      <div class="sat-card"><div class="sat-label" id="sl2">Signal strength</div><div class="sat-val" id="sigVal">98.4%</div><div class="sat-sub">Excellent</div></div>
      <div class="sat-card"><div class="sat-label" id="sl3">Location accuracy</div><div class="sat-val">±1.2m</div><div class="sat-sub">Sub-meter</div></div>
      <div class="sat-card"><div class="sat-label" id="sl4">Data uplink</div><div class="sat-val" id="uplinkVal">124 Mbps</div><div class="sat-sub">Ku-band</div></div>
      <div class="sat-card"><div class="sat-label" id="sl5">Latitude</div><div class="sat-val">13.21°N</div><div class="sat-sub">Chittoor</div></div>
      <div class="sat-card"><div class="sat-label" id="sl6">Longitude</div><div class="sat-val">79.10°E</div><div class="sat-sub">IST +5:30</div></div>
    </div>
    <div style="font-size:11px;color:rgba(255,255,255,0.4);margin-top:6px" id="satFeat">Features: SOS beacon · Live vehicle tracking · Weather feed · Emergency broadcast · QR sync · IoT sensor data · Smart pole network · CCTV relay</div>
  </div>
  <div class="qr-connect">
    <svg class="qr-svg-w" viewBox="0 0 80 80" xmlns="http://www.w3.org/2000/svg">
      <rect width="80" height="80" fill="white" rx="5"/>
      <rect x="8" y="8" width="24" height="24" fill="none" stroke="#185FA5" stroke-width="2.5" rx="2"/>
      <rect x="13" y="13" width="14" height="14" fill="#185FA5" rx="1"/>
      <rect x="48" y="8" width="24" height="24" fill="none" stroke="#185FA5" stroke-width="2.5" rx="2"/>
      <rect x="53" y="13" width="14" height="14" fill="#185FA5" rx="1"/>
      <rect x="8" y="48" width="24" height="24" fill="none" stroke="#185FA5" stroke-width="2.5" rx="2"/>
      <rect x="13" y="53" width="14" height="14" fill="#185FA5" rx="1"/>
      <rect x="48" y="48" width="6" height="6" fill="#185FA5" rx="1"/>
      <rect x="58" y="48" width="6" height="6" fill="#185FA5" rx="1"/>
      <rect x="48" y="58" width="6" height="6" fill="#185FA5" rx="1"/>
      <rect x="58" y="58" width="6" height="6" fill="#185FA5" rx="1"/>
      <rect x="36" y="8" width="6" height="6" fill="#185FA5" rx="1"/>
      <rect x="36" y="18" width="6" height="6" fill="#185FA5" rx="1"/>
      <rect x="8" y="36" width="6" height="6" fill="#185FA5" rx="1"/>
      <rect x="18" y="36" width="6" height="6" fill="#185FA5" rx="1"/>
      <rect x="36" y="36" width="6" height="6" fill="#185FA5" rx="1"/>
    </svg>
    <div class="qr-info">
      <h3 id="qrh">QR → Satellite Connection</h3>
      <p id="qrp">Scanning this QR code syncs your phone to the pole's satellite uplink. You receive real-time GPS tracking, emergency SOS, live bus/train feeds, and all smart city services — even offline via NavIC.</p>
    </div>
  </div>
  <div class="g3">
    <div class="stat"><div class="sl" id="iot1">IoT sensors</div><div class="sv">24</div><div class="su">on this pole</div></div>
    <div class="stat"><div class="sl" id="iot2">CCTV feeds</div><div class="sv">6</div><div class="su">live streams</div></div>
    <div class="stat"><div class="sl" id="iot3">Uptime</div><div class="sv">99.7%</div><div class="su">this month</div></div>
  </div>
</div>

<div id="p-weather" class="panel">
  <div class="g2">
    <div class="card">
      <div class="ct"><i class="ti ti-thermometer" aria-hidden="true"></i><span id="wt1">Temperature</span></div>
      <div class="weather-big">32°C</div>
      <div style="font-size:13px;color:var(--color-text-secondary);margin-top:4px" id="wdesc">Partly Cloudy</div>
      <div style="font-size:12px;color:var(--color-text-secondary);margin-top:6px" id="wfeels">Feels like 36°C · Humidity 68%</div>
    </div>
    <div class="card">
      <div class="ct"><i class="ti ti-leaf" aria-hidden="true"></i><span id="wt2">Air Quality</span></div>
      <div style="font-size:38px;font-weight:500;color:#BA7517">87</div>
      <div class="prog-bar2"><div class="prog-marker" style="left:22%"></div></div>
      <div style="font-size:12px;font-weight:500;color:#BA7517" id="aqil">Moderate · Wear mask outdoors</div>
    </div>
  </div>
  <div class="g3">
    <div class="stat"><div class="sl" id="ws1">Wind</div><div class="sv">14<span class="su"> km/h</span></div></div>
    <div class="stat"><div class="sl" id="ws2">UV Index</div><div class="sv">8<span class="su">/11</span></div></div>
    <div class="stat"><div class="sl" id="ws3">Visibility</div><div class="sv">7<span class="su"> km</span></div></div>
    <div class="stat"><div class="sl" id="ws4">Rain chance</div><div class="sv">22<span class="su">%</span></div></div>
    <div class="stat"><div class="sl" id="ws5">Sunrise</div><div class="sv" style="font-size:16px">05:58</div></div>
    <div class="stat"><div class="sl" id="ws6">Sunset</div><div class="sv" style="font-size:16px">18:34</div></div>
  </div>
  <div class="card">
    <div class="ct"><i class="ti ti-calendar" aria-hidden="true"></i><span id="wfc">5-Day Satellite Forecast</span></div>
    <div class="row"><span style="font-size:13px;color:var(--color-text-primary);width:80px" id="wd1">Today</span><span style="font-size:13px;flex:1;color:var(--color-text-secondary)">⛅ Partly cloudy</span><span style="font-size:13px;font-weight:500">28–35°C</span></div>
    <div class="row"><span style="font-size:13px;color:var(--color-text-primary);width:80px" id="wd2">Tomorrow</span><span style="font-size:13px;flex:1;color:var(--color-text-secondary)">🌧 Light rain</span><span style="font-size:13px;font-weight:500">25–31°C</span></div>
    <div class="row"><span style="font-size:13px;color:var(--color-text-primary);width:80px" id="wd3">Day 3</span><span style="font-size:13px;flex:1;color:var(--color-text-secondary)">☀ Sunny</span><span style="font-size:13px;font-weight:500">27–34°C</span></div>
    <div class="row"><span style="font-size:13px;color:var(--color-text-primary);width:80px" id="wd4">Day 4</span><span style="font-size:13px;flex:1;color:var(--color-text-secondary)">⛈ Thunderstorm</span><span style="font-size:13px;font-weight:500">24–29°C</span></div>
    <div class="row"><span style="font-size:13px;color:var(--color-text-primary);width:80px" id="wd5">Day 5</span><span style="font-size:13px;flex:1;color:var(--color-text-secondary)">⛅ Partly cloudy</span><span style="font-size:13px;font-weight:500">26–33°C</span></div>
  </div>
</div>

<div id="p-tourism" class="panel">
  <div class="card">
    <div class="ct"><i class="ti ti-camera" aria-hidden="true"></i><span id="tourt">Tourist Attractions · Chittoor & Nearby</span></div>
    <div class="tour-c"><div class="tour-ic" style="background:#FAEEDA">🛕</div><div><div class="tour-name" id="tr1">Sri Kanipakam Vinayaka Temple</div><div class="tour-desc" id="trd1">Famous Swayambhu Ganesha temple, one of the most visited shrines in Andhra Pradesh.</div><div class="tour-tags"><span class="tour-tag">Religious</span><span class="tour-tag">26 km</span><span class="tour-tag">Free entry</span></div></div></div>
    <div class="tour-c"><div class="tour-ic" style="background:#E1F5EE">🏔</div><div><div class="tour-name" id="tr2">Horsley Hills</div><div class="tour-desc" id="trd2">Scenic hill station at 1265m, popular for trekking and nature walks.</div><div class="tour-tags"><span class="tour-tag">Nature</span><span class="tour-tag">37 km</span><span class="tour-tag">Trekking</span></div></div></div>
    <div class="tour-c"><div class="tour-ic" style="background:#E6F1FB">🦚</div><div><div class="tour-name" id="tr3">Talakona Waterfalls</div><div class="tour-desc" id="trd3">Highest waterfall in AP at 270 feet, inside Sri Venkateswara National Park.</div><div class="tour-tags"><span class="tour-tag">Nature</span><span class="tour-tag">54 km</span><span class="tour-tag">Wildlife</span></div></div></div>
    <div class="tour-c"><div class="tour-ic" style="background:#FBEAF0">🐘</div><div><div class="tour-name" id="tr4">Koundinya Wildlife Sanctuary</div><div class="tour-desc" id="trd4">Home to Asian elephants, leopards, and diverse flora. Best Oct–March.</div><div class="tour-tags"><span class="tour-tag">Wildlife</span><span class="tour-tag">48 km</span><span class="tour-tag">Entry fee</span></div></div></div>
    <div class="tour-c"><div class="tour-ic" style="background:#EAF3DE">🏰</div><div><div class="tour-name" id="tr5">Chandragiri Fort</div><div class="tour-desc" id="trd5">Historic 11th century fort of the Vijayanagara Empire with a museum.</div><div class="tour-tags"><span class="tour-tag">Heritage</span><span class="tour-tag">15 km</span><span class="tour-tag">Museum</span></div></div></div>
  </div>
</div>

<div id="p-wifi" class="panel">
  <div class="card">
    <div class="ct"><i class="ti ti-wifi" aria-hidden="true"></i><span id="wft">Free Wi-Fi Zones · Satellite Backhaul</span></div>
    <div class="wifi-z"><i class="ti ti-wifi" aria-hidden="true"></i><div><div class="wifi-name">SmartCity_Chittoor_5G</div><div class="wifi-info" id="wf1">Free · No password · 200 Mbps · Satellite backhauled</div></div><span class="badge gb" style="margin-left:auto">Active</span></div>
    <div class="wifi-z"><i class="ti ti-wifi" aria-hidden="true"></i><div><div class="wifi-name">RailwayStation_FreeWiFi</div><div class="wifi-info" id="wf2">Free · OTP login · 20 Mbps · RailTel</div></div><span class="badge gb" style="margin-left:auto">Active</span></div>
    <div class="wifi-z" style="background:#FAEEDA;border-color:#FAC775"><i class="ti ti-wifi" aria-hidden="true" style="color:#854F0B"></i><div><div class="wifi-name" style="color:#412402">BusStand_AP_WiFi</div><div class="wifi-info" style="color:#633806" id="wf3">Free · Phone OTP · Maintenance mode</div></div><span class="badge ab" style="margin-left:auto">Limited</span></div>
  </div>
  <div class="card">
    <div class="ct"><i class="ti ti-device-mobile" aria-hidden="true"></i><span id="svt">Smart Pole Digital Services</span></div>
    <div class="row"><i class="ti ti-printer" style="font-size:14px;margin-right:10px;color:var(--color-text-secondary)" aria-hidden="true"></i><span style="font-size:13px;flex:1" id="sv1">Document printing · CSC kiosk</span><span class="badge bb">200m</span></div>
    <div class="row"><i class="ti ti-building-bank" style="font-size:14px;margin-right:10px;color:var(--color-text-secondary)" aria-hidden="true"></i><span style="font-size:13px;flex:1" id="sv2">ATM / banking kiosk</span><span class="badge bb">50m</span></div>
    <div class="row"><i class="ti ti-scan" style="font-size:14px;margin-right:10px;color:var(--color-text-secondary)" aria-hidden="true"></i><span style="font-size:13px;flex:1" id="sv3">Aadhaar / e-Seva counter</span><span class="badge bb">150m</span></div>
    <div class="row"><i class="ti ti-charging-pile" style="font-size:14px;margin-right:10px;color:var(--color-text-secondary)" aria-hidden="true"></i><span style="font-size:13px;flex:1" id="sv4">Phone charging station (solar)</span><span class="badge gb">Here</span></div>
    <div class="row"><i class="ti ti-eye" style="font-size:14px;margin-right:10px;color:var(--color-text-secondary)" aria-hidden="true"></i><span style="font-size:13px;flex:1" id="sv5">CCTV surveillance active</span><span class="badge gb">Live</span></div>
    <div class="row"><i class="ti ti-alarm" style="font-size:14px;margin-right:10px;color:var(--color-text-secondary)" aria-hidden="true"></i><span style="font-size:13px;flex:1" id="sv6">Satellite SOS emergency button</span><span class="badge rb">24/7</span></div>
  </div>
</div>

<div id="p-announce" class="panel">
  <div class="card">
    <div class="ct"><i class="ti ti-speakerphone" aria-hidden="true"></i><span id="ant">Government Alerts · Live Broadcast</span></div>
    <div class="ann-item"><span class="ann-tag">Transport</span><div class="ann-text" id="an1">MG Road closed 10AM–4PM for maintenance. Use NH40 alternate.</div><div class="ann-date">Today · Municipal Corp</div></div>
    <div class="ann-item"><span class="ann-tag" style="background:var(--color-background-success);color:var(--color-text-success)">Health</span><div class="ann-text" id="an2">Free eye checkup camp at District Hospital on May 10. Walk-in accepted.</div><div class="ann-date">May 6 · DHO</div></div>
    <div class="ann-item"><span class="ann-tag" style="background:var(--color-background-warning);color:var(--color-text-warning)">Weather</span><div class="ann-text" id="an3">Heavy rain warning for Chittoor district on May 8. Avoid low-lying areas.</div><div class="ann-date">May 6 · IMD</div></div>
    <div class="ann-item"><span class="ann-tag">Water</span><div class="ann-text" id="an4">Water supply interrupted in Ward 5 from 10AM–2PM for pipeline repairs.</div><div class="ann-date">Today · Municipality</div></div>
    <div class="ann-item"><span class="ann-tag" style="background:var(--color-background-danger);color:var(--color-text-danger)">Alert</span><div class="ann-text" id="an5">Satellite SOS triggered at Pole CIT-QR-0039 · Emergency teams dispatched.</div><div class="ann-date">12 min ago · SmartCity Control</div></div>
    <div class="ann-item"><span class="ann-tag">Education</span><div class="ann-text" id="an6">Free skill development training at Govt Polytechnic. Register before May 15.</div><div class="ann-date">May 5 · Collector Office</div></div>
  </div>
</div>

<div id="p-complaint" class="panel">
  <div class="card">
    <div class="ct"><i class="ti ti-message-circle" aria-hidden="true"></i><span id="cpt">Complaint / Feedback · Satellite Logged</span></div>
    <div class="complaint-form">
      <select id="ccat"><option>Select category...</option><option>Road / Infrastructure</option><option>Water Supply</option><option>Electricity</option><option>Garbage / Sanitation</option><option>Public Safety</option><option>Transport</option><option>Hospital / Health</option><option>Satellite Pole Issue</option><option>Other</option></select>
      <input type="text" id="cname" placeholder="Your name (optional)">
      <input type="tel" id="cphone" placeholder="Phone number">
      <textarea id="cdesc" placeholder="Describe your complaint or feedback..."></textarea>
      <button class="sub-btn" onclick="submitC()" id="csub">Submit · Satellite Logged</button>
      <div class="smsg" id="smsg">Complaint submitted via satellite. Reference: <strong id="refid"></strong> · SMS update within 2 hrs · Average resolution: 2.4 days</div>
    </div>
  </div>
  <div class="g3">
    <div class="stat"><div class="sl">Resolved (week)</div><div class="sv">142</div></div>
    <div class="stat"><div class="sl">In progress</div><div class="sv">38</div></div>
    <div class="stat"><div class="sl">Avg resolution</div><div class="sv" style="font-size:15px">2.4d</div></div>
  </div>
</div>
</div>

<script>
const buses=[
  {num:'AP37A',name:'Chittoor → Tirupati',via:'via Puttur',dist:87,occ:85,eta:'3 min',status:'On route',col:'#185FA5',badge:'bb'},
  {num:'AP12B',name:'Chittoor → Vellore',via:'via NH40',dist:72,occ:60,eta:'11 min',status:'Approaching',col:'#0F6E56',badge:'gb'},
  {num:'AP-99',name:'Chittoor → Bangalore',via:'via Hosur',dist:195,occ:40,eta:'27 min',status:'Departing',col:'#BA7517',badge:'ab'},
  {num:'AP-55',name:'Chittoor → Kuppam',via:'via Palamaner',dist:58,occ:70,eta:'18 min',status:'On route',col:'#0F6E56',badge:'gb'},
  {num:'AP22C',name:'Chittoor → Madanapalle',via:'via Punganur',dist:108,occ:20,eta:'45 min',status:'Delayed',col:'#A32D2D',badge:'rb'},
  {num:'AP-7X',name:'Chittoor → Chennai',via:'via Ranipet',dist:145,occ:95,eta:'52 min',status:'Almost full',col:'#185FA5',badge:'bb'},
  {num:'AP-14',name:'Chittoor → Hyderabad',via:'via NH44',dist:580,occ:55,eta:'1h 20m',status:'Express',col:'#534AB7',badge:'pb'},
  {num:'AP-88',name:'Chittoor → Nellore',via:'via NH16',dist:220,occ:35,eta:'2h 05m',status:'On route',col:'#0F6E56',badge:'gb'},
];
const trains=[
  {num:'12691',name:'Chennai → Delhi Rajdhani',via:'via Vijayawada',eta:'14:35',plat:'2',status:'On time',delay:'—',col:'#639922',badge:'gb'},
  {num:'17230',name:'Tirupati → Secunderabad',via:'via Renigunta',eta:'16:10',plat:'1',status:'5 min late',delay:'+5',col:'#BA7517',badge:'ab'},
  {num:'12658',name:'Chennai → Bangalore',via:'via Katpadi',eta:'18:45',plat:'3',status:'On time',delay:'—',col:'#639922',badge:'gb'},
  {num:'11042',name:'Mumbai → Chennai Exp',via:'via Pune',eta:'21:20',plat:'2',status:'22 min late',delay:'+22',col:'#A32D2D',badge:'rb'},
  {num:'12616',name:'Grand Trunk Express',via:'via Waltair',eta:'23:05',plat:'1',status:'On time',delay:'—',col:'#639922',badge:'gb'},
  {num:'07115',name:'Tirupati → Hyderabad',via:'via Cuddapah',eta:'08:15',plat:'4',status:'On time',delay:'—',col:'#639922',badge:'gb'},
];
const hosps=[
  {av:'CH',bg:'#B5D4F4',tc:'#042C53',name:'City General Hospital',dist:'0.3 km',open:'24/7',beds:'34/120',wait:'~20 min',ph:'08572-234567',tags:['Emergency','ICU','Surgery','Pharmacy','Blood Bank'],status:'Open',sb:'gb'},
  {av:'GH',bg:'#9FE1CB',tc:'#04342C',name:'Govt District Hospital',dist:'1.1 km',open:'24/7',beds:'67/200',wait:'~35 min',ph:'08572-226600',tags:['Emergency','Maternity','Pediatrics','Free OPD'],status:'Open',sb:'gb'},
  {av:'SC',bg:'#FAC775',tc:'#412402',name:'Sri Clinic & Diagnostics',dist:'0.6 km',open:'8AM–9PM',beds:'—',wait:'~15 min',ph:'08572-241100',tags:['Lab Tests','X-Ray','Ultrasound','ECG'],status:'Open',sb:'gb'},
  {av:'RH',bg:'#CECBF6',tc:'#26215C',name:'Rainbow Children\'s Hospital',dist:'2.1 km',open:'24/7',beds:'40/80',wait:'~25 min',ph:'08572-260000',tags:['Pediatrics','NICU','Vaccination','Neurology'],status:'Open',sb:'gb'},
  {av:'MC',bg:'#F4C0D1',tc:'#4B1528',name:'Mother & Child Care Centre',dist:'1.8 km',open:'9AM–8PM',beds:'17/40',wait:'~40 min',ph:'08572-255010',tags:['Gynecology','NICU','Vaccination'],status:'Busy',sb:'ab'},
  {av:'EH',bg:'#F7C1C1',tc:'#501313',name:'Emergency Health Unit',dist:'0.5 km',open:'24/7',beds:'8/20',wait:'Immediate',ph:'08572-299911',tags:['Trauma','Burns','Poison','Fracture'],status:'Open',sb:'gb'},
];

function buildBusList(){
  const el=document.getElementById('busListEl');
  el.innerHTML=buses.map(b=>`
    <div class="bus-card">
      <div class="bc-head">
        <div class="bc-num">${b.num}</div>
        <div style="flex:1"><div class="bc-name">${b.name}</div><div style="font-size:11px;color:var(--color-text-secondary)">${b.via}</div></div>
        <span style="font-size:14px;font-weight:500;color:${b.col}">${b.eta}</span>
      </div>
      <div class="prog"><div class="prog-f" style="width:${b.occ}%;background:${b.col}"></div></div>
      <div class="bc-meta">
        <div class="bc-m"><i class="ti ti-user" aria-hidden="true"></i>${b.occ}% full</div>
        <div class="bc-m"><i class="ti ti-road" aria-hidden="true"></i>${b.dist} km</div>
        <div class="bc-m"><i class="ti ti-antenna" aria-hidden="true"></i>NavIC GPS</div>
        <span class="badge ${b.badge}" style="margin-left:auto">${b.status}</span>
      </div>
    </div>`).join('');
}

function buildTrainList(){
  const el=document.getElementById('trainListEl');
  el.innerHTML=trains.map(t=>`
    <div class="row">
      <div style="min-width:46px"><span class="badge bb" style="font-size:10px">${t.num}</span></div>
      <div style="flex:1;margin:0 10px">
        <div style="font-size:13px;color:var(--color-text-primary)">${t.name}</div>
        <div style="font-size:11px;color:var(--color-text-secondary)">${t.via} · Platform ${t.plat} · ETA ${t.eta}</div>
      </div>
      <div style="text-align:right">
        <span class="badge ${t.badge}">${t.status}</span>
        ${t.delay!=='—'?`<div style="font-size:11px;color:#A32D2D;margin-top:2px">${t.delay} min</div>`:''}
      </div>
    </div>`).join('');
}

function buildHospList(){
  const el=document.getElementById('hospListEl');
  el.innerHTML=hosps.map(h=>`
    <div class="hosp-card">
      <div class="hc-head">
        <div class="hc-av" style="background:${h.bg};color:${h.tc}">${h.av}</div>
        <div style="flex:1"><div class="hc-name">${h.name}</div><div class="hc-dist">${h.dist} · ${h.open}</div></div>
        <span class="badge ${h.sb}">${h.status}</span>
      </div>
      <div class="hc-tags">${h.tags.map(t=>`<span class="hc-tag">${t}</span>`).join('')}</div>
      ${h.beds!=='—'?`<div class="hc-row"><span>Available beds</span><span>${h.beds}</span></div>`:''}
      <div class="hc-row"><span>Wait time</span><span>${h.wait}</span></div>
      <div class="hc-row"><span>Phone</span><span style="color:var(--color-text-info)">${h.ph}</span></div>
    </div>`).join('');
}

const tickerItems=[
  {col:'#639922',txt:'Bus AP37A: 3 min to Chittoor Station'},
  {col:'#185FA5',txt:'Train 12691: On time at Platform 2'},
  {col:'#A32D2D',txt:'Alert: Heavy rain warning May 8'},
  {col:'#BA7517',txt:'Bus AP22C: 45 min · Delayed 12 min'},
  {col:'#0F6E56',txt:'City Hospital: 34 beds available'},
  {col:'#534AB7',txt:'NavIC satellite lock: 12 sats active'},
  {col:'#993C1D',txt:'Flight AI-505: Tirupati arrival 15:20'},
  {col:'#185FA5',txt:'Bus AP-7X: 52 min · Almost full'},
  {col:'#639922',txt:'SmartCity Pole CIT-0042: All systems normal'},
  {col:'#A32D2D',txt:'Emergency resolved: Pole CIT-0039 · 8 min response'},
];

function buildTicker(){
  const items=[...tickerItems,...tickerItems];
  document.getElementById('tickerInner').innerHTML=items.map(t=>`
    <div class="ticker-item">
      <div class="ticker-dot" style="background:${t.col}"></div>
      <span>${t.txt}</span>
    </div>`).join('');
}

const layers={bus:true,train:false,flight:false};
function toggleLayer(l,btn){
  layers[l]=!layers[l];
  btn.classList.toggle('on',layers[l]);
  const show=layers[l]?'':'none';
  document.querySelectorAll(`#layer-${l} *`).forEach(el=>el.style.display=show);
  if(l==='bus'){['busA','busB','busC'].forEach(id=>{const e=document.getElementById(id);if(e)e.style.display=show});}
  if(l==='train'){['trainA','trainB'].forEach(id=>{const e=document.getElementById(id);if(e)e.style.display=show});}
  if(l==='flight'){['flightA','flightB'].forEach(id=>{const e=document.getElementById(id);if(e)e.style.display=show});}
}

function cityClick(city){
  const info={Delhi:'Delhi: 1,284 active buses · 312 trains · 42 QR poles',Kolkata:'Kolkata: 892 buses · 208 trains · 38 QR poles',Mumbai:'Mumbai: 2,100 buses · 480 trains · 96 QR poles',Hyderabad:'Hyderabad: 1,560 buses · 310 trains · 65 QR poles',Bengaluru:'Bengaluru: 1,820 buses · 286 trains · 78 QR poles',Chennai:'Chennai: 1,340 buses · 340 trains · 72 QR poles',Jaipur:'Jaipur: 620 buses · 125 trains · 28 QR poles',Bhopal:'Bhopal: 480 buses · 98 trains · 22 QR poles',Guwahati:'Guwahati: 320 buses · 72 trains · 14 QR poles',Chittoor:'Chittoor (YOU): 6 live bus routes · 6 trains · Satellite: LIVE'};
  const el=document.getElementById('city-info');
  if(el)el.textContent=info[city]||city;
}

function showP(id,btn){
  document.querySelectorAll('.panel').forEach(p=>p.classList.remove('on'));
  document.querySelectorAll('.nb').forEach(b=>b.classList.remove('on'));
  document.getElementById('p-'+id).classList.add('on');
  btn.classList.add('on');
}

function submitC(){
  const desc=document.getElementById('cdesc').value;
  if(!desc.trim()){alert('Please describe your complaint.');return;}
  const ref='SAT'+Math.floor(10000+Math.random()*90000);
  document.getElementById('refid').textContent=ref;
  document.getElementById('smsg').style.display='block';
  document.getElementById('cdesc').value='';
  document.getElementById('cname').value='';
  document.getElementById('cphone').value='';
}

let busX=[162,225,270],busDir=[1,1,-1],busTgts=[[100,280],[185,300],[220,140]];
function animateBuses(){
  const ids=['busA','busB','busC'];
  ids.forEach((id,i)=>{
    const el=document.getElementById(id);
    if(!el||!layers.bus)return;
    const cx=parseFloat(el.getAttribute('x'))||busX[i];
    busX[i]+=busDir[i]*0.6;
    if(busX[i]>320)busDir[i]=-1;
    if(busX[i]<80)busDir[i]=1;
    el.setAttribute('x',Math.round(busX[i]));
  });
  const tIds=['trainA','trainB'];
  const txs=[200,238],tDirs=[1,-1];
  tIds.forEach((id,i)=>{
    const el=document.getElementById(id);
    if(!el||!layers.train)return;
    const cx=parseFloat(el.getAttribute('cx'))||txs[i];
    txs[i]+=tDirs[i]*0.4;
    if(txs[i]>310)tDirs[i]=-1;
    if(txs[i]<100)tDirs[i]=1;
    el.setAttribute('cx',Math.round(txs[i]));
  });
  requestAnimationFrame(animateBuses);
}

let sig=98.4,uplink=124;
setInterval(()=>{
  sig=Math.max(94,Math.min(99.9,sig+(Math.random()-0.5)*0.3));
  uplink=Math.max(100,Math.min(148,uplink+(Math.random()-0.5)*2));
  const sv=document.getElementById('sigVal');
  const uv=document.getElementById('uplinkVal');
  if(sv)sv.textContent=sig.toFixed(1)+'%';
  if(uv)uv.textContent=Math.round(uplink)+' Mbps';
  const ss4=document.getElementById('ss4');
  if(ss4){const s=Math.ceil(Math.random()*4);ss4.textContent=(curL==='en'?'Last sync: ':'Sync: ')+s+'s ago';}
},2000);

const orbitEls=[
  {id:'os1',radius:30,angle:0,speed:1.5},
  {id:'os2',radius:45,angle:120,speed:1},
  {id:'os3',radius:45,angle:240,speed:1},
  {id:'os4',radius:58,angle:60,speed:0.7},
];
function animateOrbits(){
  orbitEls.forEach(o=>{
    o.angle=(o.angle+o.speed)%360;
    const rad=o.angle*Math.PI/180;
    const cx=70+Math.cos(rad)*o.radius;
    const cy=70+Math.sin(rad)*o.radius;
    const el=document.getElementById(o.id);
    if(el){el.style.left=(cx-7)+'px';el.style.top=(cy-7)+'px';}
  });
  requestAnimationFrame(animateOrbits);
}

let curL='en';
const LT={
  en:{n:['India Map','Bus Track','Trains','Hospitals','Emergency','Satellite','Weather','Tourism','Wi-Fi','Alerts','Complaint'],ss:['NavIC satellite: LIVE','GPS lock: 12 sats','Signal: 98.4%','Last sync: 2s ago']},
  hi:{n:['भारत नक्शा','बस ट्रैक','ट्रेन','अस्पताल','आपातकाल','उपग्रह','मौसम','पर्यटन','Wi-Fi','अलर्ट','शिकायत'],ss:['NavIC उपग्रह: सक्रिय','GPS लॉक: 12 सैट','सिग्नल: 98.4%','अंतिम सिंक: 2s']},
  te:{n:['భారత మ్యాప్','బస్ ట్రాక్','రైళ్ళు','ఆస్పత్రులు','అత్యవసరం','ఉపగ్రహం','వాతావరణం','పర్యాటకం','Wi-Fi','హెచ్చరికలు','ఫిర్యాదు'],ss:['NavIC: లైవ్','GPS: 12 శాటిలైట్','సిగ్నల్: 98.4%','సమన్వయం: 2s']},
  ta:{n:['இந்திய வரைபடம்','பேருந்து','ரயில்கள்','மருத்துவமனை','அவசரநிலை','செயற்கைக்கோள்','வானிலை','சுற்றுலா','Wi-Fi','எச்சரிக்கை','புகார்'],ss:['NavIC: நேரடி','GPS: 12 துணைக்கோள்கள்','சிக்னல்: 98.4%','ஒத்திசைவு: 2s']},
  bn:{n:['ভারতের মানচিত্র','বাস ট্র্যাক','ট্রেন','হাসপাতাল','জরুরি','স্যাটেলাইট','আবহাওয়া','পর্যটন','Wi-Fi','সতর্কতা','অভিযোগ'],ss:['NavIC: সরাসরি','GPS: ১২ স্যাটেলাইট','সিগনাল: ৯৮.৪%','সিঙ্ক: ২s']},
  mr:{n:['भारत नकाशा','बस ट्रॅक','रेल्वे','रुग्णालय','आपत्कालीन','उपग्रह','हवामान','पर्यटन','Wi-Fi','सूचना','तक्रार'],ss:['NavIC: थेट','GPS: १२ उपग्रह','संकेत: ९८.४%','सिंक: २s']},
  fr:{n:['Carte Inde','Bus Live','Trains','Hôpitaux','Urgence','Satellite','Météo','Tourisme','Wi-Fi','Alertes','Plainte'],ss:['NavIC: EN DIRECT','GPS: 12 sats','Signal: 98.4%','Sync: il y a 2s']},
  de:{n:['Indien-Karte','Bus-Live','Züge','Krankenhäuser','Notfall','Satellit','Wetter','Tourismus','WLAN','Warnungen','Beschwerde'],ss:['NavIC: LIVE','GPS: 12 Sats','Signal: 98,4%','Sync: vor 2s']},
  zh:{n:['印度地图','实时公交','火车','医院','紧急','卫星','天气','旅游','Wi-Fi','公告','投诉'],ss:['NavIC：实时','GPS：12颗卫星','信号：98.4%','同步：2秒前']},
  ja:{n:['インド地図','バス追跡','鉄道','病院','緊急','衛星','天気','観光','Wi-Fi','警報','苦情'],ss:['NavIC：ライブ','GPS：12衛星','信号：98.4%','同期：2秒前']},
  ar:{n:['خريطة الهند','تتبع الحافلة','القطارات','المستشفيات','الطوارئ','القمر الاصطناعي','الطقس','السياحة','Wi-Fi','التنبيهات','الشكاوى'],ss:['NavIC: مباشر','GPS: 12 قمر','الإشارة: 98.4%','مزامنة: قبل 2s']},
};
function setL(l,btn){
  curL=l;
  document.querySelectorAll('.lb').forEach(b=>b.classList.remove('on'));
  btn.classList.add('on');
  const d=LT[l]||LT.en;
  if(d.n){const ids=['n1','n2','n3','n4','n5','n6','n7','n8','n9','n10','n11'];d.n.forEach((v,i)=>{const e=document.getElementById(ids[i]);if(e)e.textContent=v;});}
  if(d.ss){const ids=['ss1','ss2','ss3','ss4'];d.ss.forEach((v,i)=>{const e=document.getElementById(ids[i]);if(e)e.textContent=v;});}
}

buildBusList();
buildTrainList();
buildHospList();
buildTicker();
animateBuses();
animateOrbits();
</script>

</body>
</html>
