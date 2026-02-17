
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PREDICTOR MACHINE 2.0</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }body {
  background: #0f172a;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  color: #fff;
}

.start-screen {
  position: fixed; inset: 0; background: #020617;
  display: flex; flex-direction: column; justify-content: center; align-items: center; z-index: 10;
}

.start-screen h1 { font-size: 24px; color: #38bdf8; margin-bottom: 20px; text-align: center; }

.start-btn {
  padding: 12px 28px; border: none; border-radius: 999px; font-size: 16px; font-weight: bold;
  background: #22c55e; color: #000; cursor: pointer; box-shadow: 0 8px 20px rgba(0,0,0,0.4);
  transition: transform 0.2s ease, opacity 0.2s ease;
}

.start-btn:active { transform: scale(0.95); opacity: 0.8; }

.container {
  width: 380px; background: #020617; border-radius: 20px; padding: 16px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.5); display: none;
}

.title { text-align: center; font-size: 20px; font-weight: bold; margin-bottom: 12px; color: #38bdf8; }

.section { background: #0f172a; border-radius: 14px; padding: 10px; margin-bottom: 10px; }

.section h2 { font-size: 14px; margin-bottom: 6px; color: #facc15; }

.match {
  background: #020617; padding: 8px; border-radius: 8px; margin-bottom: 6px; font-size: 12px;
  display: flex; justify-content: space-between; align-items: center;
}

.tip { color: #22c55e; font-weight: bold; }

.total-odds { margin-top: 6px; text-align: center; font-size: 12px; font-weight: bold; color: #22c55e; }

.date { text-align: center; font-size: 11px; opacity: 0.7; margin-bottom: 8px; }

.footer { text-align: center; font-size: 10px; opacity: 0.6; margin-top: 6px; }

  </style>
</head>
<body>  <!-- Start Screen -->  <div class="start-screen" id="startScreen">
    <h1>PREDICTOR MACHINE 2.0</h1>
    <button class="start-btn" onclick="startApp()">START</button>
  </div>  <!-- Main Content -->  <div class="container" id="mainContent">
    <div class="title">🔥 DAILY ROLLOVER ODDS</div><div class="date">17 Feb 2026</div>

<!-- 1.30+ Section -->
<div class="section">
  <h2>Rollover 1.30+ Odds</h2>
  <div class="match"><span>Benfica  vs Real Madrid</span><span class="tip">Over 1.5</span></div>
  <div class="match"><span>Monaco vs P.S.G</span><span class="tip">Over 1.5</span></div>
  
  

<!-- 1.50+ Section -->
<div class="section">
  <h2>Rollover 1.50+ Odds</h2>
  <div class="match"><span>Bristol Rovers vs Wrexham</span><span class="tip">Home Over 0.5</span></div>
  <div class="match"><span>Benfica vs Real Madrid</span><span class="tip">Away Over 0.5</span></div>
  

<!-- 2.00+ Section -->
<div class="section">
  <h2>Rollover 2.00+ Odds</h2>
  <div class="match"><span>Benfica vs Real Madrid</span><span class="tip">Home Over 0.5 </span></div>
  <div class="match"><span>Borussia vs Atalanta</span><span class="tip">Home Over 0.5</span></div>


<div class="match"><span>Galatasaray vs Juventus</span><span class="tip">Home Over 0.5</span></div>


  
</div>

<div class="footer">Win Smart • Play Safe</div>

  </div>  <script>
    function startApp() {
      document.getElementById('startScreen').style.display = 'none';
      document.getElementById('mainContent').style.display = 'block';
    }
  </script>
