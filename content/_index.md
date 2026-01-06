<div class="relative flex flex-col items-center justify-center min-h-[50vh] text-center px-4 py-20 overflow-hidden">
  
  <style>
    @keyframes crack-breathe {
      0%, 100% { 
        opacity: 0.4; 
        filter: blur(1px); 
        letter-spacing: 0.5em;
        transform: scale(1) skewX(0deg);
      }
      50% { 
        opacity: 0.2; 
        filter: blur(2.5px); 
        letter-spacing: 0.55em; 
        transform: scale(1.02) skewX(-1deg);
      }
    }
    .animate-broken-mirror {
      animation: crack-breathe 4.5s ease-in-out infinite;
    }
  </style>

  <div class="flex flex-col items-center group cursor-default select-none z-10 relative space-y-1 transition-transform duration-1000 group-hover:-translate-y-4">
    <h1 class="font-bold uppercase text-3xl md:text-5xl text-slate-600 dark:text-slate-300 tracking-[0.2em] leading-none transition-all duration-700 group-hover:text-slate-900 dark:group-hover:text-white group-hover:tracking-[0.3em]">
      Breaking
    </h1>
    <div class="relative perspective-1000 pt-2"> <div class="font-bold uppercase text-3xl md:text-6xl
                   text-slate-500 dark:text-slate-400/60
                   animate-broken-mirror
                   transition-all duration-[1200ms] ease-out
                   group-hover:animate-none 
                   group-hover:opacity-100 
                   group-hover:blur-0 
                   group-hover:tracking-[0.35em] 
                   group-hover:scale-100
                   group-hover:transform-none
                   tracking-[0.5em]
                   ">
        <span>M</span><span>I</span><span style="color: #4f46e5; filter: drop-shadow(0 0 8px rgba(79,70,229,0.5));" class="dark:text-indigo-400">R</span><span style="color: #e11d48; filter: drop-shadow(0 0 8px rgba(225,29,72,0.5));" class="dark:text-rose-500">R</span><span>O</span><span style="color: #d6d3d1; filter: drop-shadow(0 0 5px rgba(255,255,255,0.4));" class="dark:text-stone-200">R</span><span>S</span>
      </div>
    </div>
    <div class="w-[1px] h-8 bg-neutral-300/40 dark:bg-neutral-600/40 mt-6 !mb-6 transition-all duration-1000 group-hover:h-12 group-hover:bg-neutral-400 dark:group-hover:bg-neutral-500"></div>
    <div class="text-[10px] md:text-xs font-serif uppercase tracking-[0.3em] text-neutral-300 dark:text-neutral-600 transition-all duration-1000 group-hover:text-neutral-500 dark:group-hover:text-neutral-400 group-hover:tracking-[0.5em]">
       <span style="color: #4f46e5; filter: drop-shadow(0 0 4px rgba(79,70,229,0.3)); opacity: 0.8;">R</span><span>E</span><span>V</span><span>E</span><span style="color: #e11d48; filter: drop-shadow(0 0 4px rgba(225,29,72,0.3)); opacity: 0.8;">R</span><span>I</span><span>E</span><span style="color: #d6d3d1; filter: drop-shadow(0 0 4px rgba(255,255,255,0.2)); opacity: 0.8;">R</span>
    </div>
  </div>

  <div class="w-full max-w-6xl px-4 z-0 relative mt-4">
    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-2/3 h-2/3 bg-primary-500/10 dark:bg-primary-400/10 blur-[100px] rounded-full -z-10 opacity-0 group-hover:opacity-100 transition-opacity duration-[2000ms]"></div>
    {{< figure 
        src="Reverier.png" 
        class="w-full rounded-[2px] shadow-2xl mx-auto grayscale-[70%] contrast-[85%] brightness-90 hover:grayscale-0 hover:contrast-100 hover:brightness-100 transition-all duration-[1500ms] ease-in-out hover:-translate-y-1"
    >}}
  </div>
  
</div>



