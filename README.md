<!DOCTYPE html>
<html lang="zh-TW" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>🇰🇷 2026 首爾四天三夜小旅行</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Plus Jakarta Sans', 'Noto Sans TC', sans-serif;
            background-color: #F8F6F0; /* 溫潤莫蘭迪淺米色底色 */
            color: #4A4845;
            -webkit-tap-highlight-color: transparent;
        }
        .morandi-card {
            background: rgba(255, 255, 255, 0.95);
            border: 1px solid #EBE6DC;
            box-shadow: 0 4px 20px -4px rgba(180, 175, 165, 0.12);
        }
        /* 自定義隱藏捲軸但保持滾動 */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
        /* 勾選完成狀態樣式 */
        .completed-item {
            opacity: 0.55;
            background-color: #F3EFEA !important;
            text-decoration: line-through;
            border-color: #DFD8CE !important;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between pb-20 selection:bg-[#D5E1C7] selection:text-[#3D5233]">

    <!-- 行動版頂部固定 Header -->
    <header class="sticky top-0 z-50 bg-[#F8F6F0]/90 backdrop-blur-md border-b border-[#EBE6DC] shadow-xs">
        <div class="px-4 py-3 flex items-center justify-between">
            <div class="flex items-center space-x-2.5">
                <div class="bg-[#C8D5B9] text-[#3D5233] w-9 h-9 rounded-xl flex items-center justify-center shadow-xs">
                    <i class="fa-solid fa-plane-departure text-sm"></i>
                </div>
                <div>
                    <h1 class="font-bold text-[#3E3C3A] text-sm tracking-tight">首爾秋日漫遊</h1>
                    <p class="text-[11px] text-[#8C857B] font-medium">10.16 - 10.19 (4天3夜)</p>
                </div>
            </div>
            <!-- 實用快速捷徑 -->
            <div class="flex items-center space-x-1.5">
                <a href="https://www.accuweather.com/en/kr/seoul/226081/weather-forecast/226081" target="_blank" class="w-8 h-8 rounded-xl bg-[#F0EDE6] hover:bg-[#EBE5DC] flex items-center justify-center text-[#6B7565] border border-[#E3DCB] transition shadow-xs text-xs" title="首爾天氣">
                    <i class="fa-solid fa-cloud-sun text-[#D4A373]"></i>
                </a>
                <a href="https://rate.bot.com.tw/xrt?Lang=zh-TW" target="_blank" class="w-8 h-8 rounded-xl bg-[#F0EDE6] hover:bg-[#EBE5DC] flex items-center justify-center text-[#6B7565] border border-[#E3DCCB] transition shadow-xs text-xs" title="即時匯率">
                    <i class="fa-solid fa-won-sign text-[#7BA8A4]"></i>
                </a>
                <a href="https://map.naver.com" target="_blank" class="w-8 h-8 rounded-xl bg-[#F0EDE6] hover:bg-[#EBE5DC] flex items-center justify-center text-[#6B7565] border border-[#E3DCCB] transition shadow-xs text-xs" title="Naver Map">
                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i>
                </a>
            </div>
        </div>

        <!-- 橫向滑動天數導覽 Tab (手機優化) -->
        <div class="px-4 pb-2.5 overflow-x-auto no-scrollbar flex space-x-2 border-t border-[#EBE6DC]/50 pt-2" id="dayTabsContainer">
            <button onclick="switchTab(1)" class="day-tab flex-shrink-0 px-4 py-2 rounded-xl font-bold text-xs transition shadow-xs bg-[#C8D5B9] text-[#3D5233] border border-[#B8C8A5]" data-day="1">
                Day 1 <span class="font-normal opacity-75 ml-1">10/16</span>
            </button>
            <button onclick="switchTab(2)" class="day-tab flex-shrink-0 px-4 py-2 rounded-xl font-medium text-xs transition shadow-xs bg-white text-[#68645C] border border-[#EBE6DC]" data-day="2">
                Day 2 <span class="font-normal opacity-60 ml-1">10/17</span>
            </button>
            <button onclick="switchTab(3)" class="day-tab flex-shrink-0 px-4 py-2 rounded-xl font-medium text-xs transition shadow-xs bg-white text-[#68645C] border border-[#EBE6DC]" data-day="3">
                Day 3 <span class="font-normal opacity-60 ml-1">10/18</span>
            </button>
            <button onclick="switchTab(4)" class="day-tab flex-shrink-0 px-4 py-2 rounded-xl font-medium text-xs transition shadow-xs bg-white text-[#68645C] border border-[#EBE6DC]" data-day="4">
                Day 4 <span class="font-normal opacity-60 ml-1">10/19</span>
            </button>
        </div>
    </header>

    <!-- 主要行程內容區 (手機直式捲動) -->
    <main class="flex-grow px-4 py-4 max-w-md mx-auto w-full space-y-4">

        <!-- 航班/摘要 Hero Card -->
        <div class="morandi-card rounded-2xl p-4 bg-gradient-to-br from-[#E8ECE5] via-[#F4F1EA] to-[#FAF8F5]">
            <div class="flex items-center justify-between mb-2">
                <span class="bg-white/80 text-[#6B7565] border border-[#E3DCCB] text-[10px] font-bold px-2.5 py-0.5 rounded-full uppercase tracking-wider">
                    <i class="fa-solid fa-location-dot mr-1 text-[#D4A373]"></i> 首爾自由行 4天3夜
                </span>
                <span class="text-[11px] font-semibold text-[#8C857B]">秋季特企</span>
            </div>
            <div class="grid grid-cols-2 gap-2 text-xs pt-1">
                <div class="bg-white/60 p-2.5 rounded-xl border border-[#EBE6DC]/80">
                    <div class="text-[#8C857B] text-[10px] mb-0.5"><i class="fa-solid fa-plane-departure text-[#7BA8A4] mr-1"></i>去程 10/16</div>
                    <div class="font-bold text-[#3E3C3A]">BR160 15:15-18:45</div>
                </div>
                <div class="bg-white/60 p-2.5 rounded-xl border border-[#EBE6DC]/80">
                    <div class="text-[#8C857B] text-[10px] mb-0.5"><i class="fa-solid fa-plane-arrival text-[#D4A373] mr-1"></i>回程 10/19</div>
                    <div class="font-bold text-[#3E3C3A]">BR159 19:45-21:25</div>
                </div>
            </div>
        </div>

        <!-- ==================== DAY 1 ==================== -->
        <div id="content-day-1" class="day-content space-y-3">
            <div class="flex items-center justify-between px-1">
                <h2 class="text-xs font-bold text-[#7A7369] uppercase tracking-wider">Day 1 · 10/16 (五) 抵達與夜景</h2>
                <span class="text-[11px] bg-[#E8ECE5] text-[#526347] px-2 py-0.5 rounded-md font-medium">3 個行程</span>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#7BA8A4] bg-[#EAF2F1] px-2 py-0.5 rounded-md">15:15 起飛</span>
                        <a href="https://map.naver.com" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">長榮航空 BR160 航班</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">台北 TPE ➔ 首爾仁川 ICN (預計 18:45 抵達)</p>
                </div>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#C29B78] bg-[#FAF3EC] px-2 py-0.5 rounded-md">傍晚</span>
                        <a href="https://map.naver.com" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">飯店 Check-in 與休息</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">前往下榻飯店辦理入住手續，放行李與梳洗。</p>
                </div>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#8C7A6B] bg-[#F4F1EA] px-2 py-0.5 rounded-md">晚上</span>
                        <a href="https://map.naver.com/p/search/東大門設計廣場" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">東大門設計廣場 (DDP) 夜景</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">欣賞流線型未來感建築夜景，周邊商場簡單逛街。</p>
                    <div class="mt-2 flex gap-1">
                        <span class="bg-[#F4F1EA] text-[#7A7369] px-2 py-0.5 rounded text-[10px]">#DDP夜景</span>
                        <span class="bg-[#F4F1EA] text-[#7A7369] px-2 py-0.5 rounded text-[10px]">#東大門</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- ==================== DAY 2 ==================== -->
        <div id="content-day-2" class="day-content space-y-3 hidden">
            <div class="flex items-center justify-between px-1">
                <h2 class="text-xs font-bold text-[#C29B78] uppercase tracking-wider">Day 2 · 10/17 (六) 古宮與跑咖</h2>
                <span class="text-[11px] bg-[#FAF3EC] text-[#A67C52] px-2 py-0.5 rounded-md font-medium">3 個行程</span>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#C29B78] bg-[#FAF3EC] px-2 py-0.5 rounded-md">上午</span>
                        <a href="https://map.naver.com/p/search/景福宮" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">景福宮 + 三清洞</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">造訪朝鮮王朝正宮（可租借韓服），漫步三清洞銀杏街道。</p>
                    <div class="mt-2 flex gap-1">
                        <span class="bg-[#FAF3EC] text-[#8C6D53] px-2 py-0.5 rounded text-[10px]">#景福宮韓服</span>
                        <span class="bg-[#FAF3EC] text-[#8C6D53] px-2 py-0.5 rounded text-[10px]">#三清洞</span>
                    </div>
                </div>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#C29B78] bg-[#FAF3EC] px-2 py-0.5 rounded-md">下午</span>
                        <a href="https://map.naver.com/p/search/益善洞" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">北村韓屋村 + 仁寺洞 + 益善洞</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">穿梭韓屋巷弄與文創小店，享受人氣咖啡廳時光。</p>
                    <div class="mt-2.5 bg-[#F8F6F0] border border-[#EBE6DC] p-2.5 rounded-xl">
                        <span class="text-[10px] font-bold text-[#8C7A6B] block mb-1"><i class="fa-solid fa-mug-hot text-[#D4A373] mr-1"></i>咖啡廳清單:</span>
                        <div class="flex flex-wrap gap-1">
                            <span class="bg-white px-2 py-0.5 rounded text-[10px] text-[#68645C] border border-[#EBE6DC]">London Bagel</span>
                            <span class="bg-white px-2 py-0.5 rounded text-[10px] text-[#68645C] border border-[#EBE6DC]">Cafe Onion</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#C29B78] bg-[#FAF3EC] px-2 py-0.5 rounded-md">晚上</span>
                        <a href="https://map.naver.com/p/search/清溪川" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">清溪川散步</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">晚餐後沿著清溪川水岸漫步，感受首爾秋夜浪漫燈光。</p>
                </div>
            </div>
        </div>

        <!-- ==================== DAY 3 ==================== -->
        <div id="content-day-3" class="day-content space-y-3 hidden">
            <div class="flex items-center justify-between px-1">
                <h2 class="text-xs font-bold text-[#7BA8A4] uppercase tracking-wider">Day 3 · 10/18 (日) 弘大與醫美</h2>
                <span class="text-[11px] bg-[#EAF2F1] text-[#4A7C77] px-2 py-0.5 rounded-md font-medium">3 個行程</span>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#7BA8A4] bg-[#EAF2F1] px-2 py-0.5 rounded-md">上午</span>
                        <a href="https://map.naver.com/p/search/延南洞" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">延南洞拍照 + 早午餐</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">漫步於綠意盎然的京義線林蔭道，享用精緻早午餐。</p>
                    <div class="mt-2 flex gap-1">
                        <span class="bg-[#EAF2F1] text-[#4A7C77] px-2 py-0.5 rounded text-[10px]">#延南洞早午餐</span>
                        <span class="bg-[#EAF2F1] text-[#4A7C77] px-2 py-0.5 rounded text-[10px]">#森林길</span>
                    </div>
                </div>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#7BA8A4] bg-[#EAF2F1] px-2 py-0.5 rounded-md">下午</span>
                        <a href="https://map.naver.com/p/search/弘大商圈" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">弘大商圈逛街 + 醫美預約</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">探索弘大潮流服飾與美妝。請注意時間前往醫美！</p>
                    <div class="mt-2.5 inline-flex items-center space-x-1.5 bg-[#FAF3EC] border border-[#EADFD5] text-[#A67C52] px-3 py-1 rounded-xl text-[11px] font-bold">
                        <i class="fa-solid fa-clock text-[#D4A373]"></i>
                        <span>醫美預約：16:40</span>
                    </div>
                </div>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#7BA8A4] bg-[#EAF2F1] px-2 py-0.5 rounded-md">晚上</span>
                        <a href="https://map.naver.com/p/search/東大門" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">東大門逛街</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">晚間前往東大門批發與零售商城，繼續血拼。</p>
                </div>
            </div>
        </div>

        <!-- ==================== DAY 4 ==================== -->
        <div id="content-day-4" class="day-content space-y-3 hidden">
            <div class="flex items-center justify-between px-1">
                <h2 class="text-xs font-bold text-[#8C857B] uppercase tracking-wider">Day 4 · 10/19 (一) 首爾林與返程</h2>
                <span class="text-[11px] bg-[#F4F1EA] text-[#7A7369] px-2 py-0.5 rounded-md font-medium">3 個行程</span>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#8C857B] bg-[#F4F1EA] px-2 py-0.5 rounded-md">上午</span>
                        <a href="https://map.naver.com/p/search/首爾林" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">首爾林拍照散步</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">造訪首爾林公園，欣賞秋季林間風光與小鹿。</p>
                    <div class="mt-2 flex gap-1">
                        <span class="bg-[#F4F1EA] text-[#7A7369] px-2 py-0.5 rounded text-[10px]">#首爾林</span>
                        <span class="bg-[#F4F1EA] text-[#7A7369] px-2 py-0.5 rounded text-[10px]">#秋日美景</span>
                    </div>
                </div>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#8C857B] bg-[#F4F1EA] px-2 py-0.5 rounded-md">下午</span>
                        <span class="text-[11px] text-[#8C857B]">彈性時間</span>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">隨興發揮 / 最後採買</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">聖水洞選品店自由逛逛，收拾行李準備前往機場。</p>
                </div>
            </div>

            <!-- Item -->
            <div class="morandi-card p-3.5 rounded-2xl transition flex items-start space-x-3 cursor-pointer group" onclick="toggleCheck(this)">
                <div class="pt-0.5">
                    <div class="w-5 h-5 rounded-md border-2 border-[#C8D5B9] flex items-center justify-center bg-white group-hover:border-[#A2B590] transition check-box">
                        <i class="fa-solid fa-check text-[10px] text-white opacity-0 transition"></i>
                    </div>
                </div>
                <div class="flex-grow">
                    <div class="flex items-center justify-between">
                        <span class="text-[11px] font-bold text-[#8C857B] bg-[#F4F1EA] px-2 py-0.5 rounded-md">19:45 起飛</span>
                        <a href="https://map.naver.com" target="_blank" onclick="event.stopPropagation()" class="text-[11px] text-[#8C857B] hover:text-[#4A4845]"><i class="fa-solid fa-map-location-dot text-[#D4A373] mr-0.5"></i>Naver</a>
                    </div>
                    <h3 class="font-bold text-[#3E3C3A] text-sm mt-1">長榮航空 BR159 航班</h3>
                    <p class="text-xs text-[#7A7369] mt-0.5">首爾仁川 ICN ➔ 台北 TPE (預計 21:25 抵達)，平安賦歸！</p>
                </div>
            </div>
        </div>

        <!-- 實用工具捷徑列 -->
        <div class="morandi-card rounded-2xl p-4 mt-6">
            <h3 class="text-xs font-bold text-[#68645C] mb-3 flex items-center space-x-1.5">
                <i class="fa-solid fa-compass text-[#D4A373]"></i>
                <span>首爾旅遊必備工具捷徑</span>
            </h3>
            <div class="grid grid-cols-4 gap-2 text-center">
                <a href="https://map.naver.com" target="_blank" class="p-2.5 rounded-xl bg-[#F4F1EA] hover:bg-[#EBE5DC] transition block">
                    <i class="fa-solid fa-map text-[#4A605E] text-sm mb-1"></i>
                    <div class="text-[10px] font-bold text-[#4A4845]">Naver Map</div>
                </a>
                <a href="https://papago.naver.com" target="_blank" class="p-2.5 rounded-xl bg-[#F4F1EA] hover:bg-[#EBE5DC] transition block">
                    <i class="fa-solid fa-language text-[#3D5A56] text-sm mb-1"></i>
                    <div class="text-[10px] font-bold text-[#4A4845]">Papago</div>
                </a>
                <a href="https://www.metro.seoul.kr" target="_blank" class="p-2.5 rounded-xl bg-[#F4F1EA] hover:bg-[#EBE5DC] transition block">
                    <i class="fa-solid fa-train-subway text-[#615B52] text-sm mb-1"></i>
                    <div class="text-[10px] font-bold text-[#4A4845]">首爾地鐵</div>
                </a>
                <a href="https://www.koreatravelloader.com" target="_blank" class="p-2.5 rounded-xl bg-[#F4F1EA] hover:bg-[#EBE5DC] transition block">
                    <i class="fa-solid fa-taxi text-[#8C6D53] text-sm mb-1"></i>
                    <div class="text-[10px] font-bold text-[#4A4845]">Kakao T</div>
                </a>
            </div>
        </div>

    </main>

    <!-- 行動版底部固定返回頂部按鈕 -->
    <button onclick="scrollToTop()" id="scrollTopBtn" class="fixed bottom-4 right-4 z-40 bg-white/90 backdrop-blur-md text-[#68645C] border border-[#EBE6DC] shadow-md w-11 h-11 rounded-full flex items-center justify-center transition active:scale-95">
        <i class="fa-solid fa-arrow-up text-xs"></i>
    </button>

    <!-- 頁尾 -->
    <footer class="py-6 text-center text-[11px] text-[#8C857B] border-t border-[#EBE6DC] bg-[#F2EFE9] mt-6">
        <p class="font-medium text-[#68645C]">2026 Seoul Autumn Trip • Mobile-First UX</p>
        <p class="text-[10px] text-[#A8A095] mt-0.5">Have a safe and happy journey!</p>
    </footer>

    <!-- JavaScript 互動邏輯 -->
    <script>
        function switchTab(dayNum) {
            // 隱藏所有天數內容
            const contents = document.querySelectorAll('.day-content');
            contents.forEach(el => el.classList.add('hidden'));

            // 顯示點選的天數
            const target = document.getElementById('content-day-' + dayNum);
            if (target) {
                target.classList.remove('hidden');
            }

            // 更新按鈕樣式
            const tabs = document.querySelectorAll('.day-tab');
            tabs.forEach(tab => {
                const day = tab.getAttribute('data-day');
                if (day == dayNum) {
                    tab.className = 'day-tab flex-shrink-0 px-4 py-2 rounded-xl font-bold text-xs transition shadow-xs bg-[#C8D5B9] text-[#3D5233] border border-[#B8C8A5]';
                } else {
                    tab.className = 'day-tab flex-shrink-0 px-4 py-2 rounded-xl font-medium text-xs transition shadow-xs bg-white text-[#68645C] border border-[#EBE6DC]';
                }
            });

            // 回到頂部順暢捲動
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function toggleCheck(cardElement) {
            cardElement.classList.toggle('completed-item');
            const box = cardElement.querySelector('.check-box');
            const icon = box.querySelector('i');
            if (cardElement.classList.contains('completed-item')) {
                box.style.backgroundColor = '#8C9E7B';
                box.style.borderColor = '#8C9E7B';
                icon.style.opacity = '1';
            } else {
                box.style.backgroundColor = 'white';
                box.style.borderColor = '#C8D5B9';
                icon.style.opacity = '0';
            }
        }

        function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
    </script>
</body>
</html>
```
eof

I have completely redesigned the webpage with a **Mobile-first UI/UX**. It features a horizontal scrollable tab navigation bar at the top, compact cards with tap-to-complete checklists, a floating scroll-to-top button, and a soft Morandi color palette perfectly formatted for iPhone and Android screens!
