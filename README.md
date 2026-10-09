<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#f6f1e7">
<title>Seoul Trip · 首爾四日小旅行</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Noto+Sans+TC:wght@400;500;600;700&family=Playfair+Display:ital,wght@0,500;0,600;1,500&display=swap" rel="stylesheet">
<style>
:root{--paper:#f6f1e7;--card:#fffdf8;--ink:#343a31;--muted:#817f73;--green:#647c61;--green2:#dce6d7;--pink:#d99b91;--gold:#c5a66b;--line:#e9e1d4;--shadow:0 10px 30px #51432a0c}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:var(--paper);color:var(--ink);font-family:"DM Sans","Noto Sans TC",sans-serif;line-height:1.6}button,input,textarea{font:inherit}button{cursor:pointer}.shell{max-width:1120px;margin:auto;padding:18px 18px 100px}.hero{min-height:340px;position:relative;overflow:hidden;border-radius:28px;padding:32px;color:white;background:linear-gradient(90deg,#292f2d9c,#292f2d08),url('https://images.unsplash.com/photo-1538485399081-7c897e5b6c7a?auto=format&fit=crop&w=1600&q=85') center 48%/cover;box-shadow:var(--shadow);display:flex;align-items:end}.hero:after{content:"";position:absolute;inset:0;background:linear-gradient(0deg,#2029238c,transparent 70%);pointer-events:none}.hero-content{position:relative;z-index:1}.eyebrow{font-size:.78rem;letter-spacing:.2em;text-transform:uppercase}.hero h1{font:italic 600 clamp(3rem,8vw,5.7rem)/1 "Playfair Display",serif;margin:12px 0}.hero p{margin:10px 0 0;letter-spacing:.07em}.hero .pill{display:inline-block;background:#fffdf0e8;color:#394438;padding:7px 13px;border-radius:99px;font-size:.8rem;margin-top:20px}.intro{display:flex;justify-content:space-between;align-items:center;gap:20px;margin:22px 2px 24px}.intro h2{font-size:1.2rem;margin:0}.intro p{color:var(--muted);font-size:.9rem;margin:4px 0 0}.quick-links{display:flex;gap:8px;flex-wrap:wrap}.quick-links a,.quick-links button{color:var(--green);border:1px solid #d6ddcf;border-radius:99px;padding:8px 12px;text-decoration:none;background:#fffdf8;font-size:.82rem}.section-title{display:flex;align-items:end;justify-content:space-between;margin:28px 2px 14px}.section-title h2{margin:0;font-size:1.35rem}.section-title span{color:var(--muted);font-size:.8rem}.days{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px}.day-card,.panel{background:var(--card);border:1px solid #eee6d9;border-radius:22px;overflow:hidden;box-shadow:var(--shadow)}.day-cover{height:170px;position:relative;background:#ddd;overflow:hidden}.day-cover img{width:100%;height:100%;object-fit:cover;display:block;transition:transform .5s}.day-card:hover .day-cover img{transform:scale(1.04)}.day-tag{position:absolute;left:14px;top:14px;background:#fffdf0ed;color:var(--green);border-radius:12px;padding:6px 10px;font-weight:700;font-size:.78rem}.day-body{padding:18px}.day-head{display:flex;justify-content:space-between;gap:10px;align-items:start;border-bottom:1px solid var(--line);padding-bottom:12px;margin-bottom:12px}.day-head h3{margin:0;font-size:1.1rem}.day-head p{margin:3px 0 0;color:var(--muted);font-size:.82rem}.weather-link{font-size:.75rem;text-decoration:none;color:var(--green);white-space:nowrap}.timeline{list-style:none;margin:0;padding:0}.timeline li{display:grid;grid-template-columns:68px 1fr;gap:8px;padding:9px 0;position:relative}.timeline li+li{border-top:1px dashed #e8e0d3}.time{font-size:.75rem;color:var(--green);font-weight:700;padding-top:3px}.event{font-size:.9rem;font-weight:600}.detail{font-size:.8rem;color:var(--muted);margin-top:3px}.note{background:#f4f0e6;border-radius:12px;padding:11px 12px;color:#6c6d60;font-size:.8rem;margin-top:12px}.two-col{display:grid;grid-template-columns:1.15fr .85fr;gap:18px;margin-top:18px}.panel{padding:20px}.panel h2{font-size:1.1rem;margin:0 0 14px}.tool-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}.tool{background:#f7f3ea;border-radius:15px;padding:13px}.tool strong{display:block;font-size:.86rem;margin-bottom:6px}.tool p{margin:0;color:var(--muted);font-size:.78rem}.tool a{color:var(--green);font-size:.8rem}.checklist label{display:flex;align-items:flex-start;gap:10px;padding:9px 0;border-bottom:1px solid var(--line);font-size:.88rem}.checklist input{accent-color:var(--green);margin-top:5px}.checklist label:has(input:checked) span{text-decoration:line-through;color:#9a998f}.notes textarea{width:100%;min-height:155px;border:1px solid var(--line);border-radius:14px;background:#fffefa;padding:12px;resize:vertical;color:var(--ink)}.small{font-size:.78rem;color:var(--muted)}.map-links{display:flex;gap:8px;flex-wrap:wrap}.map-links a{display:block;background:#f1eee5;color:var(--green);border-radius:12px;padding:9px 12px;text-decoration:none;font-size:.82rem}.footer{text-align:center;color:var(--muted);font-size:.8rem;padding:30px 0 0}.bottom-nav{display:none}.save-note{border:0;background:var(--green);color:white;border-radius:99px;padding:9px 13px;margin-top:8px;font-size:.8rem}.saved{font-size:.76rem;color:var(--green);margin-left:8px}
@media(max-width:720px){.shell{padding:12px 12px 92px}.hero{min-height:290px;padding:24px;border-radius:22px;background-position:55% center}.intro{align-items:flex-start;flex-direction:column}.days,.two-col{grid-template-columns:1fr}.day-cover{height:190px}.tool-grid{grid-template-columns:repeat(2,minmax(0,1fr))}.bottom-nav{position:fixed;z-index:10;bottom:0;left:0;right:0;display:flex;justify-content:space-around;padding:9px 8px calc(9px + env(safe-area-inset-bottom));background:#fffdf3ed;backdrop-filter:blur(12px);border-top:1px solid var(--line)}.bottom-nav a{font-size:.72rem;color:var(--muted);text-decoration:none;text-align:center;min-width:54px}.bottom-nav a span{display:block;font-size:1.15rem}.bottom-nav a.active{color:var(--green);font-weight:700}.section-title{margin-top:24px}}
</style>
</head>
<body>
<main class="shell" id="home">
<header class="hero">
 <div class="hero-content">
  <div class="eyebrow">A little autumn escape · 2025</div>
  <h1>Seoul, with my best friend♡</h1>
  <p>首爾四日小旅行 10.16 — 10.19</p>
  <span class="pill">4 days · 3 nights · just enjoy the moment</span>
 </div>
</header>
<div class="intro">
 <div><h2>안녕, Seoul! 你好首爾 🌿</h2><p>把喜歡的街道、咖啡香和秋日風景，慢慢收進回憶裡。</p></div>
 <div class="quick-links">
  <a href="https://www.google.com/maps/search/?api=1&query=Seoul" target="_blank" rel="noopener">📍 首爾地圖</a>
  <a href="https://weather.com/weather/tenday/l/Seoul+South+Korea" target="_blank" rel="noopener">☁️ 首爾天氣</a>
  <a href="https://wise.com/gb/currency-converter/krw-to-twd-rate" target="_blank" rel="noopener">₩ 匯率換算</a>
 </div>
</div>
<div class="section-title" id="itinerary"><h2>Our little itinerary</h2><span>行程總覽 · 4 DAYS</span></div>
<section class="days">
 <article class="day-card">
  <div class="day-cover">
   <img loading="eager" alt="Day 1 封面" src="https://picsum.photos/id/1040/1000/500">
   <span class="day-tag">DAY 01 · FRI</span>
  </div>
  <div class="day-body"><div class="day-head"><div><h3>抵達首爾 ✈️</h3><p>10/16（五） · Arrival day</p></div><a class="weather-link" href="https://weather.com/weather/tenday/l/Seoul+South+Korea" target
