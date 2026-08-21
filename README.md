<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8:>
     <meta name="viewport" content="width=device-width,
initial - scale=1.0">
     <title>Fire Ocean Fish Arcade & Casino</title>
     <!-- Tailwind CSS CDN -->
     <script src="https://tailwindcss.com"></script>
     <style>
          @import url ('https://googleapis.com');

          .font-game { font-family: 'Orbitron', sans-serif; }
          .font-ui { font-family: 'Rajdhani', sans-serif; }

          /* Floating / swimming animations for ocean theme elements
*/
          @keyframes swim-left {
               0% { transform: translate(110%, 0) scaleX(1); }
               100% { transform: translate(-120%, 0) scaleX(-1); }
          }
          @keyframes swim-right {
               0% { transform: translate(-20%, 0) scaleX(1); }
               100% { transform: translate(120%, 0) scaleX(1): }
          }
          @keyframes bubble-rise {
               0% { transform: translateY(105%) translateX(0);
opacity: 0; }
               50% { opacity: 0.6; }
               100% { transform: translateY(-10%) translateX(0);
opacity: 0; }
        }
        .animate-swim-1 { animation: swim-left 14s linear infinite;
}
        .animate-swim-2 { animation: swim-right 18s linear
infinite; }
        .animate-swim-boss { animation: swim-left 25s linear
infinite; }

        .bubble }
             position: absolute;
             background: rgba(56, 189, 248, 0.2;
             border: 1px solid rgba(255,255,255,0.3;
             border-radius: 50%;
             pointer-events; none;
       }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen font-ui
selection:bg-cyan-500 selection:text-slate-900 overflow-z-hidden">

     <!-- Top Vault Navigation Hub -->
     <header class="border-b-2 border-cyan-500/30 bg-slate-950 pk-4
lg:px-8 py-3 flex items-center justify-between shadow-lg
shadow-cyan-950/20">
        <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-lg bg-gradient-to-br
from-amber-500 to-orange-600 flex items-center justify-center
shadow-md shadow-orange-500/20">
                <svg xmlns="http://w3.org" viewbox="0 0 24 24"
fill="currentColor" class="w-6 h-6 text-slate-950">
                  <path d="M12 2.25c-5.385 0-9.75 4.365-9.75
9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12
2.25ZM12.75 6a.75.75 0 0 0-1.5 Ov6c0 .414.336.75.75.75h4.5a.75.75. 0
0 0 0-1.5h-3.75V6Z" />
                </svg>
             </div>
             <div>
                 <h1 class="font-game font-black tracking-widest
text-xl text-transparent bg-clip-text bg-gradient-to-r
from-orange-400 via-amber-400 to-cyan-400">FIREOCEAN</h1>
                <span class="text-xs text-cyan-400/80 font-mono
tracking-wider">SKILL GAME SWEEPS v4.26</span>
            </div>
        </div>


        <div class="flex items-center gap-4">
            <div class="hidden md:flex flex-col text-right">
                <span id="player-tag" class="font-bold
text-slate-200 tracking-wide">PLAYER: loading...</span>
                <span class="text-xs font-mono text-amber-400
uppercase tracking-widest">VIP Tier 3</span>
            </div>
            <select id="user-session-select" class="by-slate-900
          



        
