<!DOCTYPE html>
<html lang="zh-TW" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2026 韓國首爾四天三夜自由行</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Plus Jakarta Sans', 'Noto Sans TC', sans-serif;
            background-color: #F7F5F0; /* 溫潤淺米色底色 */
            color: #4A4A48;
        }
        .morandi-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            border: 1px solid #EAE5DC;
        }
        /* 自定義捲軸 */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #F7F5F0;
        }
        ::-webkit-scrollbar-thumb {
            -webkit-border-radius: 4px;
            border-radius: 4px;
            background: #D5CEC1;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between selection:bg-[#E3DEC3] selection:text-[#525B52]">

    <header class="sticky top-0 z-50 bg-[#F7F5F0]/90 backdrop-blur-md border-b border-[#EAE5DC] shadow-sm">
        <div class="max-w-3xl mx-auto px-5 py-3.5 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="bg-[#C8D6AF] text-[#3D5233] p-2.5 rounded-2xl shadow-sm flex items-center justify-center">
                    <i class="fa-solid fa-plane-departure text-base"></i>
                </div>
                <div>
                    <h1 class="font-bold text-[#4A4A48] text-base tracking-tight">首爾秋日慢旅</h1>
                    <p class="text-xs text-[#8C857B] font-medium">2026.10.16 - 10.19 (4天3夜)</p>
                </div>
            </div>
            <!-- 首爾實用快速連結 -->
            <div class="flex items-center space-x-2">
                <a href="https://www.accuweather.com/en/kr/seoul/226081/weather-forecast/226081" target="_blank" title="首爾天氣" class="flex items-center space-x-1.5 bg-[#FAF7F0] hover:bg-[#F2EFE9] text-[#6B7565] px-3 py-1.5 rounded-xl text-xs font-medium transition border border-[#E3DEC3] shadow-sm">
                    <i class="fa-solid fa-cloud-sun text-[#D4A373]"></i>
                    <span class="hidden sm:inline">天氣</span>
                </a>
                <a href="https://rate.bot.com.tw/xrt?Lang=zh-TW" target="_blank" title="即時匯率" class="flex items-center space-x-1.5 bg-[#FAF7F0] hover:bg-[#F2EFE9] text-[#6B7565] px-3 py-1.5 rounded-xl text-xs font-medium transition border border-[#E3DEC3] shadow-sm">
                    <i class="fa-solid fa-won-sign text-[#8CBDB9]"></i>
                    <span class="hidden sm:inline">匯率</span>
                </a>
            </div>
        </div>
    </header>

    <main class="flex-grow max-w-3xl w-full mx-auto px-5 py-6">
        <!-- Hero Banner Card (莫蘭迪色系風格) -->
        <div class="relative rounded-3xl overflow-hidden shadow-md mb-8 bg-gradient-to-br from-[#DCE4E3] via-[#EAE5DC] to-[#F3EFEA] text-[#4A4A48] p-6 sm:p-8 border border-[#E2DBD0]">
            <div class="absolute -right-10 -bottom-10 opacity-10 pointer-events-none">
                <i class="fa-solid fa-earth-asia text-[180px]"></i>
            </div>
            <div class="relative z-10 flex flex-col md:flex-row justify-between items-start md:items-center gap-6">
                <div>
                    <span class="bg-[#FAF7F0]/80 text-[#6B7565] border border-[#E3DEC3] text-xs font-semibold px-3.5 py-1 rounded-full uppercase tracking-wider inline-block mb-3 shadow-sm">
                        <i class="fa-solid fa-location-dot mr-1.5 text-[#D4A373]"></i> South Korea • Seoul
                    </span>
                    <h2 class="text-2xl sm:text-3xl font-bold tracking-tight mb-2 text-[#3A3A38]">韓國首爾自由行 🇰🇷</h2>
                    <p class="text-[#68645C] text-sm max-w-lg leading-relaxed">
                        漫步景福宮與北村韓屋，解鎖益善洞、延南洞特色咖啡廳，享受悠閒的弘大購物與東大門夜景。
                    </p>
                </div>
                <!-- 航班摘要 -->
                <div class="bg-white/70 backdrop-blur-md border border-[#EAE5DC] p-4 rounded-2xl w-full md:w-auto text-xs space-y-2 shadow-sm">
                    <div class="flex items-center justify-between space-x-4">
                        <span class="text-[#7A7369] font-medium"><i class="fa-solid fa-plane-departure mr-1 text-[#8CBDB9]"></i>去程 10/16</span>
                        <span class="font-bold text-[#4A4A48]">BR160 15:15-18:45</span>
                    </div>
                    <div class="border-t border-[#EAE5DC]/60 pt-2 flex items-center justify-between space-x-4">
                        <span class="text-[#7A7369] font-medium"><i class="fa-solid fa-plane-arrival mr-1 text-[#E6C280]"></i>回程 10/19</span>
                        <span class="font-bold text-[#4A4A48]">BR159 19:45-21:25</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- 日期導覽列 (莫蘭迪色系切換按鈕) -->
        <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 mb-6" id="dayTabs">
            <button onclick="switchTab(1)" class="day-tab px-4 py-3 rounded-2xl font-bold text-xs sm:text-sm transition shadow-sm bg-[#C8D6AF] text-[#3D5233] border border-[#B8C89F] flex flex-col items-center justify-center space-y-0.5" data-day="1">
                <span class="text-xs opacity-75 font-normal">10/16 (五)</span>
                <span>Day 1 · 抵達與夜景</span>
            </button>
            <button onclick="switchTab(2)" class="day-tab px-4 py-3 rounded-2xl font-semibold text-xs sm:text-sm transition shadow-sm bg-white text-[#68645C] hover:bg-[#FAF7F0] border border-[#EAE5DC] flex flex-col items-center justify-center space-y-0.5" data-day="2">
                <span class="text-xs opacity-60 font-normal">10/17 (六)</span>
                <span>Day 2 · 古宮與跑咖</span>
            </button>
            <button onclick="switchTab(3)" class="day-tab px-4 py-3 rounded-2xl font-semibold text-xs sm:text-sm transition shadow-sm bg-white text-[#68645C] hover:bg-[#FAF7F0] border border-[#EAE5DC] flex flex-col items-center justify-center space-y-0.5" data-day="3">
                <span class="text-xs opacity-60 font-normal">10/18 (日)</span>
                <span>Day 3 · 弘大與醫美</span>
            </button>
            <button onclick="switchTab(4)" class="day-tab px-4 py-3 rounded-2xl font-semibold text-xs sm:text-sm transition shadow-sm bg-white text-[#68645C] hover:bg-[#FAF7F0] border border-[#EAE5DC] flex flex-col items-center justify-center space-y-0.5" data-day="4">
                <span class="text-xs opacity-60 font-normal">10/19 (一)</span>
                <span>Day 4 · 首爾林返程</span>
            </button>
        </div>

        <!-- 行程詳細內容區塊 -->
        <div class="space-y-6">

            <!-- Day 1 Content -->
            <div id="content-day-1" class="day-content space-y-4">
                <div class="bg-[#EAE5DC]/60 border border-[#E2DBD0] p-4 rounded-2xl flex items-center justify-between">
                    <div>
                        <span class="text-xs font-bold text-[#7A7369] uppercase tracking-wide">Day 1</span>
                        <h3 class="text-base font-bold text-[#4A4A48]">抵達首爾 · 東大門設計廣場夜景</h3>
                    </div>
                    <span class="bg-[#DCE4E3] text-[#4A605E] text-xs px-3 py-1 rounded-xl font-medium">10/16 (五)</span>
                </div>

                <div class="grid gap-3.5">
                    <!-- Item 1 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#DCE4E3] text-[#4A605E] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            15:15
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">長榮航空 BR160 起飛</h4>
                                <span class="text-xs bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md border border-[#EAE5DC]">飛行中</span>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">台北 TPE ➔ 首爾仁川 ICN (預計 18:45 抵達)</p>
                            <div class="mt-2.5 flex items-center space-x-1.5 text-xs text-[#68645C] font-medium">
                                <i class="fa-solid fa-plane text-[#8CBDB9]"></i>
                                <span>航程約 2 小時 30 分</span>
                            </div>
                        </div>
                    </div>

                    <!-- Item 2 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#FAF0E6] text-[#A67C52] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            夜晚
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">飯店 Check-in 與休息</h4>
                                <a href="https://map.naver.com" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">前往下榻飯店辦理入住手續，放置行李與稍作梳洗。</p>
                        </div>
                    </div>

                    <!-- Item 3 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#F3E9DD] text-[#8C6D53] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            夜間
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">東大門設計廣場 (DDP) 夜景 & 簡單逛街</h4>
                                <a href="https://map.naver.com/p/search/東大門設計廣場" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">欣賞知名流線型未來感建築 DDP 的迷人夜景，並在周邊商場簡單散步逛街。</p>
                            <div class="mt-2.5 flex flex-wrap gap-1.5">
                                <span class="bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md text-[11px] border border-[#EAE5DC]">#DDP夜景</span>
                                <span class="bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md text-[11px] border border-[#EAE5DC]">#東大門商圈</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 2 Content -->
            <div id="content-day-2" class="day-content space-y-4 hidden">
                <div class="bg-[#F3E9DD]/60 border border-[#EADFD5] p-4 rounded-2xl flex items-center justify-between">
                    <div>
                        <span class="text-xs font-bold text-[#8C6D53] uppercase tracking-wide">Day 2</span>
                        <h3 class="text-base font-bold text-[#4A4A48]">古宮漫步 · 北村韓屋 · 咖啡廳馬拉松</h3>
                    </div>
                    <span class="bg-[#FAF0E6] text-[#A67C52] text-xs px-3 py-1 rounded-xl font-medium">10/17 (六)</span>
                </div>

                <div class="grid gap-3.5">
                    <!-- Item 1 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#FAF0E6] text-[#A67C52] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            上午
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">景福宮 + 三清洞</h4>
                                <a href="https://map.naver.com/p/search/景福宮" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">造訪朝鮮王朝正宮（可考慮租借韓服），隨後漫步於充滿文藝氣息與銀杏樹的三清洞街道。</p>
                            <div class="mt-2.5 flex flex-wrap gap-1.5">
                                <span class="bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md text-[11px] border border-[#EAE5DC]">#景福宮</span>
                                <span class="bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md text-[11px] border border-[#EAE5DC]">#三清洞散策</span>
                            </div>
                        </div>
                    </div>

                    <!-- Item 2 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#FAF7F0] text-[#8C857B] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            下午
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">北村韓屋村 + 仁寺洞 + 益善洞 + 跑咖</h4>
                                <a href="https://map.naver.com/p/search/益善洞" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">穿梭北村韓屋與仁寺洞文創小店，再到益善洞韓屋巷弄探訪人氣咖啡廳。</p>
                            <!-- 咖啡廳特別提醒 -->
                            <div class="mt-3 bg-[#F9F7F2] border border-[#EAE5DC] p-3 rounded-xl">
                                <span class="text-xs font-bold text-[#8C7A6B] block mb-1.5"><i class="fa-solid fa-mug-hot mr-1 text-[#D4A373]"></i> 咖啡廳清單:</span>
                                <div class="flex flex-wrap gap-1.5">
                                    <span class="bg-white text-[#68645C] px-2.5 py-1 rounded-lg text-xs font-medium border border-[#EAE5DC]">London Bagel Museum</span>
                                    <span class="bg-white text-[#68645C] px-2.5 py-1 rounded-lg text-xs font-medium border border-[#EAE5DC]">Cafe Onion 安國店</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Item 3 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#DCE4E3] text-[#4A605E] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            晚上
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">清溪川散步</h4>
                                <a href="https://map.naver.com/p/search/清溪川" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">晚餐後沿著清溪川漫步，享受首爾秋夜燈光水岸的愜意時光。</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 3 Content -->
            <div id="content-day-3" class="day-content space-y-4 hidden">
                <div class="bg-[#DCE4E3]/60 border border-[#CEDAD8] p-4 rounded-2xl flex items-center justify-between">
                    <div>
                        <span class="text-xs font-bold text-[#4A605E] uppercase tracking-wide">Day 3</span>
                        <h3 class="text-base font-bold text-[#4A4A48]">延南洞早午餐 · 弘大購物 · 醫美預約</h3>
                    </div>
                    <span class="bg-[#DCE4E3] text-[#4A605E] text-xs px-3 py-1 rounded-xl font-medium">10/18 (日)</span>
                </div>

                <div class="grid gap-3.5">
                    <!-- Item 1 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#DCE4E3] text-[#4A605E] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            上午
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">延南洞拍照 + 吃早午餐</h4>
                                <a href="https://map.naver.com/p/search/延南洞" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">漫步於浪漫綠意盎然的延南洞京義線林蔭道，享用精緻早午餐。</p>
                            <div class="mt-2.5 flex flex-wrap gap-1.5">
                                <span class="bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md text-[11px] border border-[#EAE5DC]">#延南洞早午餐</span>
                                <span class="bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md text-[11px] border border-[#EAE5DC]">#森林길拍照</span>
                            </div>
                        </div>
                    </div>

                    <!-- Item 2 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#F3E9DD] text-[#8C6D53] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            下午
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">弘大商圈逛街 & 醫美行程</h4>
                                <a href="https://map.naver.com/p/search/弘大商圈" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">探索弘大商圈潮流服飾與美妝店。請留意時間，於下午 16:40 前往醫美診所！</p>
                            <div class="mt-3 inline-flex items-center space-x-2 bg-[#FAF7F0] border border-[#E3DEC3] text-[#7A6A56] px-3.5 py-1.5 rounded-xl text-xs font-bold">
                                <i class="fa-solid fa-clock text-[#D4A373]"></i>
                                <span>醫美預約時間：16:40</span>
                            </div>
                        </div>
                    </div>

                    <!-- Item 3 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#FAF7F0] text-[#8C857B] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            晚上
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">東大門逛街</h4>
                                <a href="https://map.naver.com/p/search/東大門批發市場" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">晚間前往東大門批發與零售商城，繼續血拼戰利品。</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 4 Content -->
            <div id="content-day-4" class="day-content space-y-4 hidden">
                <div class="bg-[#F6EFEA]/80 border border-[#EADFD5] p-4 rounded-2xl flex items-center justify-between">
                    <div>
                        <span class="text-xs font-bold text-[#A67C52] uppercase tracking-wide">Day 4</span>
                        <h3 class="text-base font-bold text-[#4A4A48]">首爾林拍照 · 隨興發揮 · 返回溫暖的家</h3>
                    </div>
                    <span class="bg-[#FAF0E6] text-[#A67C52] text-xs px-3 py-1 rounded-xl font-medium">10/19 (一)</span>
                </div>

                <div class="grid gap-3.5">
                    <!-- Item 1 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#FAF0E6] text-[#A67C52] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            上午
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">首爾林拍照散步</h4>
                                <a href="https://map.naver.com/p/search/首爾林" target="_blank" class="text-xs text-[#68645C] hover:underline flex items-center space-x-1 font-medium">
                                    <i class="fa-solid fa-map-location-dot text-[#D4A373]"></i><span>Naver Map</span>
                                </a>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">造訪首爾市民喜愛的首爾林公園，欣賞秋季林間風光與可愛小鹿，非常適合拍照。</p>
                            <div class="mt-2.5 flex flex-wrap gap-1.5">
                                <span class="bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md text-[11px] border border-[#EAE5DC]">#首爾林漫步</span>
                                <span class="bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md text-[11px] border border-[#EAE5DC]">#秋日美景</span>
                            </div>
                        </div>
                    </div>

                    <!-- Item 2 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#DCE4E3] text-[#4A605E] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            下午
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">隨興發揮 / 最後採買</h4>
                                <span class="text-xs bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md border border-[#EAE5DC]">彈性時間</span>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">自由發揮時間！可在聖水洞周邊逛逛獨立選品店或咖啡廳，隨後收拾行李準備前往機場。</p>
                        </div>
                    </div>

                    <!-- Item 3 -->
                    <div class="morandi-card p-4.5 rounded-2xl shadow-sm hover:shadow transition flex items-start space-x-4">
                        <div class="bg-[#EAE5DC] text-[#5A554D] p-2.5 rounded-xl font-bold text-xs min-w-[70px] text-center">
                            19:45
                        </div>
                        <div class="flex-grow">
                            <div class="flex items-center justify-between">
                                <h4 class="font-bold text-[#4A4A48] text-sm sm:text-base">長榮航空 BR159 起飛</h4>
                                <span class="text-xs bg-[#FAF7F0] text-[#7A7369] px-2 py-0.5 rounded-md border border-[#EAE5DC]">返程航班</span>
                            </div>
                            <p class="text-xs sm:text-sm text-[#7A7369] mt-1">首爾仁川 ICN ➔ 台北 TPE (預計 21:25 抵達)，圓滿結束首爾四天三夜美好旅程！</p>
                            <div class="mt-2.5 flex items-center space-x-1.5 text-xs text-[#68645C] font-medium">
                                <i class="fa-solid fa-plane-arrival text-[#8CBDB9]"></i>
                                <span>平安賦歸</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <!-- 韓國旅遊實用工具卡片 -->
        <div class="mt-10 morandi-card rounded-3xl p-6 shadow-sm">
            <h3 class="font-bold text-[#4A4A48] text-sm mb-4 flex items-center space-x-2">
                <i class="fa-solid fa-compass text-[#D4A373]"></i>
                <span>首爾旅遊必備工具</span>
            </h3>
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3">
                <a href="https://map.naver.com" target="_blank" class="flex flex-col items-center justify-center p-3.5 rounded-2xl bg-[#FAF7F0] hover:bg-[#F2EFE9] border border-[#EAE5DC] transition text-center group">
                    <div class="w-9 h-9 rounded-xl bg-[#E2EBE5] text-[#4A605E] flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-map"></i>
                    </div>
                    <span class="text-xs font-bold text-[#4A4A48]">Naver Map</span>
                    <span class="text-[10px] text-[#8C857B] mt-0.5">韓國導航地圖</span>
                </a>
                <a href="https://papago.naver.com" target="_blank" class="flex flex-col items-center justify-center p-3.5 rounded-2xl bg-[#FAF7F0] hover:bg-[#F2EFE9] border border-[#EAE5DC] transition text-center group">
                    <div class="w-9 h-9 rounded-xl bg-[#E3EBE8] text-[#3D5A56] flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-language"></i>
                    </div>
                    <span class="text-xs font-bold text-[#4A4A48]">Papago 翻譯</span>
                    <span class="text-[10px] text-[#8C857B] mt-0.5">韓語即時翻譯</span>
                </a>
                <a href="https://www.metro.seoul.kr" target="_blank" class="flex flex-col items-center justify-center p-3.5 rounded-2xl bg-[#FAF7F0] hover:bg-[#F2EFE9] border border-[#EAE5DC] transition text-center group">
                    <div class="w-9 h-9 rounded-xl bg-[#E8E6E1] text-[#615B52] flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-train-subway"></i>
                    </div>
                    <span class="text-xs font-bold text-[#4A4A48]">首爾地鐵</span>
                    <span class="text-[10px] text-[#8C857B] mt-0.5">路線指南</span>
                </a>
                <a href="https://www.koreatravelloader.com" target="_blank" class="flex flex-col items-center justify-center p-3.5 rounded-2xl bg-[#FAF7F0] hover:bg-[#F2EFE9] border border-[#EAE5DC] transition text-center group">
                    <div class="w-9 h-9 rounded-xl bg-[#F3EBE3] text-[#8C6D53] flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                        <i class="fa-solid fa-taxi"></i>
                    </div>
                    <span class="text-xs font-bold text-[#4A4A48]">Kakao T</span>
                    <span class="text-[10px] text-[#8C857B] mt-0.5">叫車與交通</span>
                </a>
            </div>
        </div>
    </main>

    <footer class="mt-12 bg-[#EFECE6] text-[#7A7369] py-6 text-center text-xs border-t border-[#E3DEC3]">
        <div class="max-w-3xl mx-auto px-5 space-y-1">
            <p class="font-medium text-[#5A554D]">Seoul 4-Day Autumn Itinerary • Morandi Aesthetic Edition</p>
            <p class="text-[11px] text-[#9E9589]">Have a wonderful trip to Seoul!</p>
        </div>
    </footer>

    <script>
        function switchTab(dayNum) {
            // 隱藏所有行程內容
            const contents = document.querySelectorAll('.day-content');
            contents.forEach(el => el.classList.add('hidden'));

            // 顯示點選的行程內容
            const activeContent = document.getElementById('content-day-' + dayNum);
            if (activeContent) {
                activeContent.classList.remove('hidden');
            }

            // 更新按鈕莫蘭迪色彩狀態
            const tabs = document.querySelectorAll('.day-tab');
            tabs.forEach(tab => {
                const tabDay = tab.getAttribute('data-day');
                if (tabDay == dayNum) {
                    tab.className = 'day-tab px-4 py-3 rounded-2xl font-bold text-xs sm:text-sm transition shadow-sm bg-[#C8D6AF] text-[#3D5233] border border-[#B8C89F] flex flex-col items-center justify-center space-y-0.5';
                } else {
                    tab.className = 'day-tab px-4 py-3 rounded-2xl font-semibold text-xs sm:text-sm transition shadow-sm bg-white text-[#68645C] hover:bg-[#FAF7F0] border border-[#EAE5DC] flex flex-col items-center justify-center space-y-0.5';
                }
            });

            // 平滑滾動至上方
            window.scrollTo({ top: 160, behavior: 'smooth' });
        }
    </script>
</body>
</html>
```
eof

I have successfully updated the web application with a calming, gentle **Morandi color palette** (featuring soft beige, cream yellow, pastel sky blue, and sage green). You can easily copy this code into an `index.html` file and upload it directly to your GitHub repository for GitHub Pages!
