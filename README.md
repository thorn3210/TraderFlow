```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TradeFlow • Live 3-5 Month Options System • April 20 2026</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url(['https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Space+Grotesk:wght@500;600&amp;display=swap'](https://thorn3210.github.io/TraderFlow/));
        
        body { font-family: 'Inter', system_ui, sans-serif; }
        .heading-font { font-family: 'Space Grotesk', sans-serif; }
        .dark-bg { background: linear-gradient(180deg, #0a0a0a 0%, #111111 100%); }
        .glass { background: rgba(255,255,255,0.05); backdrop-filter: blur(12px); }
        .live-dot { animation: pulse 2s infinite; }
    </style>
</head>
<body class="dark-bg text-white min-h-screen pb-12">
    <!-- NAVBAR -->
    <nav class="border-b border-white/10 bg-black/90 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-6 py-5 flex items-center justify-between">
            <div class="flex items-center gap-x-3">
                <div class="w-9 h-9 bg-emerald-500 rounded-2xl flex items-center justify-center text-black font-bold text-2xl">📈</div>
                <h1 class="heading-font text-3xl tracking-tighter">TradeFlow</h1>
                <span class="px-3 py-1 text-xs font-mono bg-emerald-500/10 text-emerald-400 rounded-3xl">3-5 MONTH OPTIONS SYSTEM</span>
            </div>
            
            <div class="flex items-center gap-x-8 text-sm font-medium">
                <a onclick="document.getElementById('system').scrollIntoView({behavior:'smooth'})" class="hover:text-emerald-400 cursor-pointer">THE SYSTEM</a>
                <a onclick="document.getElementById('watchlist').scrollIntoView({behavior:'smooth'})" class="hover:text-emerald-400 cursor-pointer">WATCHLIST</a>
                <a onclick="document.getElementById('how-it-works').scrollIntoView({behavior:'smooth'})" class="hover:text-emerald-400 cursor-pointer">HOW IT WORKS</a>
                <a onclick="document.getElementById('live').scrollIntoView({behavior:'smooth'})" class="hover:text-emerald-400 cursor-pointer">LIVE STATS</a>
            </div>
            
            <div class="flex items-center gap-x-2 bg-emerald-400 text-black px-6 h-10 rounded-3xl text-sm font-semibold">
                <div class="live-dot w-2 h-2 bg-black rounded-full"></div>
                APRIL 20 2026 • LIVE
            </div>
        </div>
    </nav>

    <!-- HERO -->
    <div class="max-w-7xl mx-auto px-6 pt-16 pb-20 text-center">
        <div class="inline-flex items-center gap-x-2 bg-emerald-500/10 text-emerald-400 text-sm px-5 h-9 rounded-3xl mb-6 border border-emerald-400/30">
            <i class="fa-solid fa-handshake"></i>
            BUILT BY BURG &amp; ALAN • FOR 3-5 MONTH CONVICTION TRADERS
        </div>
        
        <h1 class="heading-font text-7xl leading-none tracking-[-2px] mb-6">
            The TradeFlow System<br>
            <span class="text-emerald-400">Conviction Plays • Real Rotation • Real Estate Endgame</span>
        </h1>
        
        <p class="text-2xl text-gray-300 max-w-2xl mx-auto">
            We scan the market, build high-conviction 3-5 month theses, rotate profits from BABA when it hits $180, and post everything transparently on our alias.<br>
            This is the exact dashboard + process we use every day.
        </p>
        
        <div class="mt-12 flex justify-center gap-x-6">
            <div class="glass px-8 py-5 rounded-3xl flex items-center gap-x-4">
                <div class="text-5xl">🚀</div>
                <div class="text-left">
                    <div class="text-emerald-400 text-sm">CURRENT BABA</div>
                    <div class="text-3xl font-semibold">$141.43 <span class="text-emerald-400 text-base">+2.05%</span></div>
                </div>
            </div>
            <div class="glass px-8 py-5 rounded-3xl flex items-center gap-x-4">
                <div class="text-5xl">🎯</div>
                <div class="text-left">
                    <div class="text-emerald-400 text-sm">NEXT BABA TARGET</div>
                    <div class="text-3xl font-semibold">$180 <span class="text-emerald-400 text-base">→ $60k unlock</span></div>
                </div>
            </div>
        </div>
    </div>

    <!-- WHAT THE SYSTEM DOES -->
    <div id="system" class="max-w-7xl mx-auto px-6 py-16 bg-black/40 border-t border-b border-white/10">
        <h2 class="heading-font text-4xl tracking-tighter text-center mb-12">What This System Actually Does</h2>
        
        <div class="grid md:grid-cols-3 gap-8">
            <div class="glass rounded-3xl p-8">
                <div class="flex items-center gap-x-4 mb-6">
                    <div class="w-12 h-12 bg-emerald-500/20 rounded-2xl flex items-center justify-center text-3xl">🔍</div>
                    <h3 class="text-2xl font-semibold">Daily Market Scan</h3>
                </div>
                <p class="text-gray-400">We run Finviz-style scans + our own filters for stocks still in clean consolidation (not the ones that already ran 100%+). Focus: 3-5 month setups with real catalysts.</p>
            </div>
            
            <div class="glass rounded-3xl p-8 border-2 border-emerald-400">
                <div class="flex items-center gap-x-4 mb-6">
                    <div class="w-12 h-12 bg-emerald-500/20 rounded-2xl flex items-center justify-center text-3xl">📝</div>
                    <h3 class="text-2xl font-semibold">Conviction Theses</h3>
                </div>
                <p class="text-gray-400">Every play gets a full thesis: why the base is forming, catalyst timeline (earnings, sector rotation, macro), and exact entry/exit levels. We only trade what we both approve.</p>
            </div>
            
            <div class="glass rounded-3xl p-8">
                <div class="flex items-center gap-x-4 mb-6">
                    <div class="w-12 h-12 bg-emerald-500/20 rounded-2xl flex items-center justify-center text-3xl">🔄</div>
                    <h3 class="text-2xl font-semibold">Profit Rotation</h3>
                </div>
                <p class="text-gray-400">When BABA hits $180 we sell half and rotate into US dips (SHOP, TSLA, etc.) or new bases like BA. Goal: scale to $300k combined → weekly options income → commercial real estate.</p>
            </div>
        </div>
    </div>

    <!-- LIVE WATCHLIST -->
    <div id="watchlist" class="max-w-7xl mx-auto px-6 py-16">
        <h2 class="heading-font text-4xl tracking-tighter mb-8 text-center">Current 3-5 Month Watchlist • April 20 2026</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
            <!-- BA -->
            <div class="glass rounded-3xl p-8">
                <div class="flex justify-between">
                    <span class="font-mono text-4xl font-semibold">BA</span>
                    <span class="px-4 py-1 bg-emerald-400/10 text-emerald-400 text-xs rounded-3xl self-start">Top Conviction</span>
                </div>
                <div class="mt-4 text-5xl font-semibold">$225.51 <span class="text-emerald-400 text-base">+3.03%</span></div>
                <div class="text-xs text-gray-400">RSI 60 • Clean base near support</div>
                <p class="text-gray-400 mt-6 text-sm">Record backlog, production ramp, defense deals. Still consolidating — perfect setup for 3-5 month move to $270+.</p>
            </div>
            
            <!-- SHOP -->
            <div class="glass rounded-3xl p-8">
                <div class="flex justify-between">
                    <span class="font-mono text-4xl font-semibold">SHOP</span>
                </div>
                <div class="mt-4 text-5xl font-semibold">$131.38 <span class="text-emerald-400 text-base">+3.81%</span></div>
                <div class="text-xs text-gray-400">RSI 61 • Near support</div>
                <p class="text-gray-400 mt-6 text-sm">AI commerce tailwinds. Tight range after dip. Classic rotation play when China rips and US pulls back.</p>
            </div>
            
            <!-- CRWD -->
            <div class="glass rounded-3xl p-8">
                <div class="flex justify-between">
                    <span class="font-mono text-4xl font-semibold">CRWD</span>
                </div>
                <div class="mt-4 text-5xl font-semibold">$423.95 <span class="text-emerald-400 text-base">+1.37%</span></div>
                <div class="text-xs text-gray-400">RSI 55 • Platform growth</div>
                <p class="text-gray-400 mt-6 text-sm">Falcon + AI momentum intact. Pulled back on rotation but fundamentals strong for next leg higher.</p>
            </div>
        </div>
    </div>

    <!-- HOW IT WORKS -->
    <div id="how-it-works" class="max-w-7xl mx-auto px-6 py-16 bg-black/40 border-t border-b border-white/10">
        <h2 class="heading-font text-4xl tracking-tighter text-center mb-12">Daily Process • What Happens Behind the Scenes</h2>
        <div class="max-w-4xl mx-auto space-y-8">
            <div class="flex gap-8 items-start glass rounded-3xl p-8">
                <div class="font-mono text-6xl font-bold text-emerald-400/30">01</div>
                <div>
                    <h4 class="font-semibold text-xl">Morning Scan</h4>
                    <p class="text-gray-400">Run market data through filters for consolidation (low recent move, RSI 50-70, price near moving averages).</p>
                </div>
            </div>
            <div class="flex gap-8 items-start glass rounded-3xl p-8">
                <div class="font-mono text-6xl font-bold text-emerald-400/30">02</div>
                <div>
                    <h4 class="font-semibold text-xl">Thesis Building</h4>
                    <p class="text-gray-400">We (Burg + Alan) review each name together. Only high-conviction plays with 2+ catalysts make it to the dashboard.</p>
                </div>
            </div>
            <div class="flex gap-8 items-start glass rounded-3xl p-8">
                <div class="font-mono text-6xl font-bold text-emerald-400/30">03</div>
                <div>
                    <h4 class="font-semibold text-xl">Public Posting</h4>
                    <p class="text-gray-400">Alias account posts full thesis + chart + “dashboard guided us here”. Transparency builds trust.</p>
                </div>
            </div>
            <div class="flex gap-8 items-start glass rounded-3xl p-8 border-2 border-emerald-400">
                <div class="font-mono text-6xl font-bold text-emerald-400/30">04</div>
                <div>
                    <h4 class="font-semibold text-xl">Profit Rotation &amp; Scaling</h4>
                    <p class="text-gray-400">When targets hit (BABA $180), we rotate into new dips/bases. Long-term goal: $300k combined → weekly options → commercial real estate.</p>
                </div>
            </div>
        </div>
    </div>

    <!-- LIVE STATS -->
    <div id="live" class="max-w-7xl mx-auto px-6 py-16">
        <h2 class="heading-font text-4xl tracking-tighter mb-8 text-center">Live Market Snapshot • April 20 2026</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
            <div class="glass rounded-3xl p-8 text-center">
                <div class="text-emerald-400 text-sm">BABA</div>
                <div class="text-4xl font-semibold">$141.43</div>
                <div class="text-emerald-400 text-sm">+2.05%</div>
            </div>
            <div class="glass rounded-3xl p-8 text-center">
                <div class="text-emerald-400 text-sm">SHOP</div>
                <div class="text-4xl font-semibold">$131.38</div>
                <div class="text-emerald-400 text-sm">+3.81%</div>
            </div>
            <div class="glass rounded-3xl p-8 text-center">
                <div class="text-emerald-400 text-sm">BA</div>
                <div class="text-4xl font-semibold">$225.51</div>
                <div class="text-emerald-400 text-sm">+3.03%</div>
            </div>
            <div class="glass rounded-3xl p-8 text-center">
                <div class="text-emerald-400 text-sm">CRWD</div>
                <div class="text-4xl font-semibold">$423.95</div>
                <div class="text-emerald-400 text-sm">+1.37%</div>
            </div>
        </div>
    </div>

    <!-- FOOTER -->
    <div class="max-w-7xl mx-auto px-6 py-12 text-center border-t border-white/10">
        <p class="text-gray-400">This is the living system we run every day. Built together. Updated live. Ready to share with the community.</p>
        <p class="text-xs text-gray-500 mt-8">TradeFlow • By Burg ❤️‍🔥 &amp; Alan Westberg • April 20 2026</p>
    </div>

    <script>
        console.log('%cTradeFlow Live System Summary loaded 🔥', 'color:#00ff9d; font-family:monospace');
    </script>
</body>
</html>
```
