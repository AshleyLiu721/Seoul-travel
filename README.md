# Seoul-travel
Seoul travel wz Lulu
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
  <h1>Seoul, with love ♡</h1>
  <p>首爾四日小旅行　10.16 — 10.19</p>
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
  <div class="day-cover"><img
  loading="eager"
  alt="東大門設計廣場夜景"
  src="https://images.unsplash.com/photo-1538485399081-7c897e5b6c7a?auto=format&fit=crop&w=1000&q=80"
  onerror="this.onerror=null;this.src='https://placehold.co/1000x500/f6f1e7/647c61?text=Seoul+DDP+Night+View';"
  style="width:100%;height:100%;object-fit:cover;"
><span class="day-tag">DAY 01 · FRI</span></div>
  <div class="day-body"><div class="day-head"><div><h3>抵達首爾 ✈️</h3><p>10/16（五） · Arrival day</p></div><a class="weather-link" href="https://weather.com/weather/tenday/l/Seoul+South+Korea" target="_blank" rel="noopener">首爾天氣 ↗</a></div>
   <ul class="timeline">
    <li><div class="time">15:15–18:45</div><div><div class="event">BR160 台北 → 仁川</div><div class="detail">飛往首爾，開始期待已久的小旅行。</div></div></li>
    <li><div class="time">晚上</div><div><div class="event">飯店 Check-in</div><div class="detail">放好行李、稍作休息，確認隔天交通。</div></div></li>
    <li><div class="time">夜景散步</div><div><div class="event">東大門設計廣場 DDP</div><div class="detail">欣賞建築夜景，附近簡單逛街、吃點東西。</div></div></li>
   </ul><div class="note">♡ 抵達日不排太滿，留一點時間給旅途的驚喜。</div>
  </div>
 </article>
 <article class="day-card">
  <div class="day-cover"><img loading="lazy" alt="景福宮韓國傳統建築" src="https://images.unsplash.com/photo-1578637387939-43c525550085?auto=format&fit=crop&w=1000&q=80"><span class="day-tag">DAY 02 · SAT</span></div>
  <div class="day-body"><div class="day-head"><div><h3>古宮 × 韓屋 × 咖啡</h3><p>10/17（六） · Old Seoul</p></div><a class="weather-link" href="https://www.google.com/maps/search/?api=1&query=Gyeongbokgung+Palace" target="_blank" rel="noopener">地圖 ↗</a></div>
   <ul class="timeline">
    <li><div class="time">上午</div><div><div class="event">景福宮 + 三清洞</div><div class="detail">欣賞宮殿建築，在三清洞巷弄散步拍照。</div></div></li>
    <li><div class="time">下午</div><div><div class="event">北村韓屋村 → 仁寺洞 → 益善洞</div><div class="detail">傳統屋瓦、文創小店與特色巷弄，一路慢慢逛。</div></div></li>
    <li><div class="time">Coffee time</div><div><div class="event">London Bagel Museum + Cafe Onion</div><div class="detail">咖啡甜點巡禮。熱門店可能需要排隊，建議預留彈性。</div><div class="map-links" style="margin-top:7px"><a href="https://www.google.com/maps/search/?api=1&query=London+Bagel+Museum+Anguk" target="_blank" rel="noopener">London Bagel ↗</a><a href="https://www.google.com/maps/search/?api=1&query=Cafe+Onion+Anguk" target="_blank" rel="noopener">Cafe Onion ↗</a></div></div></li>
    <li><div class="time">晚上</div><div><div class="event">清溪川散步</div><div class="detail">沿著溪畔走走，享受首爾夜晚的氛圍。</div></div></li>
   </ul><div class="note">♡ 景福宮、北村一帶有坡道，穿好走的鞋最重要。</div>
  </div>
 </article>
 <article class="day-card">
  <div class="day-cover"><img loading="lazy" alt="弘大街頭與商店" src="https://images.unsplash.com/photo-1517154421773-0529f29ea451?auto=format&fit=crop&w=1000&q=80"><span class="day-tag">DAY 03 · SUN</span></div>
  <div class="day-body"><div class="day-head"><div><h3>延南洞 × 弘大 × 美美變身</h3><p>10/18（日） · Cafe & Shopping</p></div><a class="weather-link" href="https://www.google.com/maps/search/?api=1&query=Yeonnam-dong+Seoul" target="_blank" rel="noopener">地圖 ↗</a></div>
   <ul class="timeline">
    <li><div class="time">上午</div><div><div class="event">延南洞拍照 + 早午餐</div><div class="detail">在特色街區散步，找間喜歡的早午餐店。</div></div></li>
    <li><div class="time">中午–下午</div><div><div class="event">弘大商圈逛街</div><div class="detail">服飾、美妝、選物店自由探索。</div></div></li>
    <li><div class="time">16:40</div><div><div class="event">醫美預約</div><div class="detail">請預留前往診所的交通與報到時間，確認預約地址。</div></div></li>
    <li><div class="time">晚上</div><div><div class="event">東大門逛街</div><div class="detail">晚餐後繼續購物；依店家營業時間彈性安排。</div></div></li>
   </ul><div class="note">♡ 醫美當天請依診所指示安排術後活動、防曬與保養。</div>
  </div>
 </article>
 <article class="day-card">
  <div class="day-cover"><img loading="lazy" alt="首爾林秋日公園" src="https://images.unsplash.com/photo-1506973035872-a4ec16b8e8d9?auto=format&fit=crop&w=1000&q=80"><span class="day-tag">DAY 04 · MON</span></div>
  <div class="day-body"><div class="day-head"><div><h3>公園漫步，帶著回憶回家</h3><p>10/19（一） · Slow morning</p></div><a class="weather-link" href="https://www.google.com/maps/search/?api=1&query=Seoul+Forest" target="_blank" rel="noopener">地圖 ↗</a></div>
   <ul class="timeline">
    <li><div class="time">上午</div><div><div class="event">首爾林拍照</div><div class="detail">享受秋日綠意、散步拍照，感受慢步調。</div></div></li>
    <li><div class="time">下午</div><div><div class="event">隨興發揮 ♡</div><div class="detail">咖啡廳、最後採買或回飯店整理行李。</div></div></li>
    <li><div class="time">建議預留</div><div><div class="event">前往仁川機場</div><div class="detail">請依飯店位置、交通方式與航空公司報到要求預留足夠時間。</div></div></li>
    <li><div class="time">19:45–21:25</div><div><div class="event">BR159 首爾 → 台北</div><div class="detail">帶著滿滿照片與回憶回家！</div></div></li>
   </ul><div class="note">♡ 回程日建議先確認行李、退稅與機場交通。</div>
  </div>
 </article>
</section>
<section class="two-col" id="tools">
 <div class="panel"><h2>Useful little links · 實用連結</h2><div class="tool-grid">
  <div class="tool"><strong>☁️ 首爾天氣</strong><p>出門前查看即時天氣與降雨。</p><a href="https://weather.com/weather/tenday/l/Seoul+South+Korea" target="_blank" rel="noopener">查看 10 日預報 ↗</a></div>
  <div class="tool"><strong>🗺️ Google Maps</strong><p>搜尋景點、店家與交通路線。</p><a href="https://www.google.com/maps/search/?api=1&query=Seoul" target="_blank" rel="noopener">開啟首爾地圖 ↗</a></div>
  <div class="tool"><strong>🚇 首爾地鐵</strong><p>路線與轉乘資訊。</p><a href="https://www.seoulmetro.co.kr/en" target="_blank" rel="noopener">Seoul Metro ↗</a></div>
  <div class="tool"><strong>💱 韓元換算</strong><p>即時匯率僅供參考，刷卡以實際入帳為準。</p><a href="https://wise.com/gb/currency-converter/krw-to-twd-rate" target="_blank" rel="noopener">KRW → TWD ↗</a></div>
  <div class="tool"><strong>🛫 航班資訊</strong><p>出發前再次確認航班與航廈。</p><a href="https://www.evaair.com/" target="_blank" rel="noopener">長榮航空官網 ↗</a></div>
  <div class="tool"><strong>🌏 韓國旅遊資訊</strong><p>旅遊公告、景點與旅遊須知。</p><a href="https://english.visitkorea.or.kr/" target="_blank" rel="noopener">Visit Korea ↗</a></div>
 </div></div>
 <div class="panel checklist" id="checklist"><h2>Little packing checklist · 必備清單</h2>
  <label><input type="checkbox"><span>護照、機票與飯店資料</span></label>
  <label><input type="checkbox"><span>信用卡、韓元、T-money 交通卡</span></label>
  <label><input type="checkbox"><span>手機、充電器、行動電源</span></label>
  <label><input type="checkbox"><span>轉接頭與充電線</span></label>
  <label><input type="checkbox"><span>舒適好走的鞋、外套</span></label>
  <label><input type="checkbox"><span>個人藥品、保養品與防曬</span></label>
  <label><input type="checkbox"><span>醫美預約資訊與診所地址</span></label>
  <label><input type="checkbox"><span>行李秤、購物袋、備用袋</span></label>
  <p class="small">勾選狀態只保存在目前頁面，重新整理後會重設。</p>
 </div>
</section>
<section class="panel notes" id="notes" style="margin-top:18px"><h2>Our travel notes · 旅行備忘錄</h2><p class="small">把飯店地址、醫美診所、預約時間或想吃的店記在這裡。此備忘錄不會上傳或自動保存。</p><textarea id="memo" placeholder="例如：飯店地址、醫美診所地址、想買的東西……"></textarea><br><button class="save-note" id="copyMemo">複製備忘錄</button><span class="saved" id="copyStatus" aria-live="polite"></span></section>
<footer class="footer">Made with ♡ for our Seoul days · 10.16 — 10.19<br>行程與營業資訊可能變動，出發前請再次確認。</footer>
</main>
<nav class="bottom-nav" aria-label="快速導覽">
 <a class="active" href="#home"><span>⌂</span>首頁</a><a href="#itinerary"><span>▦</span>行程</a><a href="#tools"><span>↗</span>實用連結</a><a href="#checklist"><span>☑</span>清單</a><a href="#notes"><span>✎</span>備忘錄</a>
</nav>
<script>
document.querySelectorAll('.bottom-nav a').forEach(a=>a.addEventListener('click',()=>{document.querySelectorAll('.bottom-nav a').forEach(x=>x.classList.remove('active'));a.classList.add('active')}));
document.getElementById('copyMemo').addEventListener('click',async()=>{const text=document.getElementById('memo').value;const status=document.getElementById('copyStatus');try{await navigator.clipboard.writeText(text);status.textContent='已複製！'}catch(e){document.getElementById('memo').select();status.textContent='請手動複製選取內容。'}});
</script>
</body>
</html>
