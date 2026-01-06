<div class="w-full min-h-[85vh] flex flex-col relative overflow-hidden group select-none cursor-default font-sans py-8">

  <style>
    @keyframes crack-breathe {
      0%, 100% { opacity: 0.5; filter: blur(1px); letter-spacing: 0.15em; transform: scale(1) skewX(0deg); }
      50% { opacity: 0.25; filter: blur(4px); letter-spacing: 0.25em; transform: scale(1.02) skewX(-1deg); }
    }
    .animate-broken-mirror { 
      animation: crack-breathe 4s ease-in-out infinite; 
      /* 默认状态：有些模糊，准备好被动画接管 */
      will-change: transform, opacity, filter;
    }
    .group:hover .animate-broken-mirror {
      animation: none !important; /* 强制停止动画 */
      opacity: 1 !important;      /* 强制不透明 */
      filter: blur(0) !important; /* 强制清晰 */
      transform: scale(1) skewX(0) !important; /* 强制回正 */
      letter-spacing: 0.2em !important; /* 强制字间距固定 */
      color: inherit;
    }
  </style>

  <div class="w-full text-left pl-4 md:pl-8 z-20">
    <div class="transition-transform duration-700 group-hover:-translate-x-1 group-hover:-translate-y-1">
      <div class="font-bold uppercase text-5xl md:text-8xl
                   text-slate-600 dark:text-slate-300
                   tracking-[0.1em]
                   leading-none">
        <span style="color: #4f46e5; filter: drop-shadow(0 0 10px rgba(79,70,229,0.5));" class="dark:text-indigo-400">R</span><span>E</span><span>V</span><span>E</span><span style="color: #e11d48; filter: drop-shadow(0 0 10px rgba(225,29,72,0.5));" class="dark:text-rose-500">R</span><span>I</span><span>E</span><span style="color: #d6d3d1; filter: drop-shadow(0 0 8px rgba(255,255,255,0.4));" class="dark:text-stone-200">R</span><span>S</span>
      </div>
    </div>
  </div>

  <div class="flex-grow flex flex-col items-center justify-center z-10 space-y-2 pb-20">
    <h2 class="font-bold uppercase text-5xl md:text-8xl 
               text-slate-700 dark:text-slate-200 
               tracking-[0.15em] 
               leading-none 
               transition-all duration-700 group-hover:tracking-[0.2em]">
      Breaking
    </h2>
    <div class="font-bold uppercase text-5xl md:text-8xl
                 text-slate-500 dark:text-slate-400/60
                 animate-broken-mirror
                 transition-all duration-1000 ease-out
                 tracking-[0.2em]
                 leading-none">
      <span>M</span><span>I</span><span style="color: #4f46e5; filter: drop-shadow(0 0 10px rgba(79,70,229,0.6));" class="dark:text-indigo-400">R</span><span style="color: #e11d48; filter: drop-shadow(0 0 10px rgba(225,29,72,0.6));" class="dark:text-rose-500">R</span><span>O</span><span style="color: #d6d3d1; filter: drop-shadow(0 0 8px rgba(255,255,255,0.5));" class="dark:text-stone-200">R</span><span>S</span>
    </div>
  </div>

  <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full h-full pointer-events-none z-0">
     <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-3/4 h-3/4 bg-slate-500/5 dark:bg-slate-400/5 blur-[100px] rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-[2000ms]"></div>
  </div>

</div>