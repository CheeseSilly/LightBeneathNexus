---
title: "Nebulaers"
date: 2025-12-30
draft: false
---

<style>
  /* 红色呼吸光效 - 用于危险能力 */
  @keyframes red-pulse {
    0% { box-shadow: 0 0 0 0 rgba(239, 68, 68, 0.4); }
    70% { box-shadow: 0 0 0 6px rgba(239, 68, 68, 0); }
    100% { box-shadow: 0 0 0 0 rgba(239, 68, 68, 0); }
  }
  .pulse-red { animation: red-pulse 2s infinite; }

  /* ========================================= */
  /* 新增：金色文字呼吸光效 (用于CLASS-S) */
  /* ========================================= */
  @keyframes gold-text-pulse {
    0%, 100% {
      color: #fde68a; /* 浅金色 */
      text-shadow: 0 0 4px #fbbf24, 0 0 8px #f59e0b; /* 基础光晕 */
    }
    50% {
      color: #ffffff; /* 高亮白 */
      text-shadow: 0 0 8px #fbbf24, 0 0 15px #f59e0b, 0 0 20px #d97706; /* 扩散光晕 */
    }
  }
  .pulse-gold-text {
    animation: gold-text-pulse 2.5s ease-in-out infinite;
  }
</style>

<div class="w-full mb-12 border-2 border-neutral-300 dark:border-neutral-600 rounded-xl overflow-hidden bg-neutral-100 dark:bg-neutral-800 shadow-md font-sans">
    <div class="relative p-6 border-b border-neutral-300 dark:border-neutral-700 bg-neutral-200/50 dark:bg-neutral-700/50 flex flex-col md:flex-row justify-between items-start md:items-center">
        <div>
            <div class="flex items-center gap-3 mb-2">
                <span class="px-2 py-0.5 text-xs font-black bg-red-600 rounded shadow-sm pulse-gold-text tracking-wider">CLASS-S</span>
                <span class="text-xs font-bold text-neutral-600 dark:text-neutral-300 uppercase tracking-widest border border-neutral-400 dark:border-neutral-500 rounded px-2 py-0.5">Human Empire</span>
            </div>
            <h2 class="text-3xl md:text-5xl font-black uppercase text-neutral-800 dark:text-white my-1 tracking-tighter">
                Iscar <span class="text-xl font-serif font-normal text-neutral-500 dark:text-neutral-400 ml-2 tracking-normal">埃斯卡</span>
            </h2>
            <div class="text-sm font-mono text-neutral-600 dark:text-neutral-300 mt-2 font-bold flex items-center gap-2">
                <span class="w-2 h-2 bg-neutral-400 rounded-full"></span>
                一体化分队 <span class="text-red-700 dark:text-red-400">"芬里尔"</span> 指挥官/前线核心
            </div>
        </div>
        <div class="mt-4 md:mt-0 text-right">
            <div class="font-black text-neutral-700 dark:text-neutral-100 text-xl uppercase tracking-widest">The General</div>
            <div class="text-xs text-neutral-500 dark:text-neutral-400 font-serif italic border-t border-neutral-400 dark:border-neutral-500 pt-1 mt-1 inline-block">"传说中的士兵"</div>
        </div>
    </div>
    <div class="p-6 bg-neutral-200 dark:bg-neutral-900/40 border-b border-neutral-300 dark:border-neutral-700 flex flex-col md:flex-row items-start gap-6">
        <div class="md:w-1/4">
            <span class="block text-xs font-bold text-neutral-500 dark:text-neutral-400 uppercase tracking-widest mb-1">The Engine</span>
            <span class="font-black text-lg text-red-700 dark:text-red-400">以太引擎 (Ether Engine)</span>
        </div>
        <div class="md:w-3/4 border-l-2 border-red-500/50 pl-4">
            <p class="text-sm text-neutral-700 dark:text-neutral-200 leading-relaxed flex items-center">
                <span class="inline-block w-2.5 h-2.5 rounded-full bg-red-600 pulse-red mr-3 flex-shrink-0"></span>
                <span>心脏位置已装载试作型以太引擎，能够配合武器释放 <strong>火道以太</strong>。</span>
            </p>
        </div>
    </div>
    <div class="p-6">
        <h3 class="text-lg font-black mb-6 border-b-2 border-neutral-800 dark:border-neutral-200 pb-2 text-neutral-800 dark:text-neutral-100 uppercase tracking-widest flex justify-between items-end">
            <span>Weapons</span>
            <span class="text-xs font-normal normal-case opacity-60">Tactical Loadout</span>
        </h3>
        <div class="mb-6 p-5 rounded bg-neutral-200/50 dark:bg-neutral-700/50 border-l-4 border-neutral-800 dark:border-neutral-200">
            <div class="font-bold text-neutral-900 dark:text-white mb-1 text-lg">
                动力巨剑
            </div>
            <p class="text-sm text-neutral-700 dark:text-neutral-300">
                可连接心脏的以太引擎，使剑刃附着 <span class="font-bold text-red-700 dark:text-red-400">高强度的以太能量</span>。
            </p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-6">
            <div class="p-4 rounded border border-neutral-300 dark:border-neutral-600 bg-neutral-200/30 dark:bg-neutral-700/30 hover:bg-neutral-200 dark:hover:bg-neutral-700 transition-colors flex flex-col">
                <div class="font-bold text-sm mb-3 text-neutral-900 dark:text-white border-b border-neutral-300 dark:border-neutral-500 pb-2 uppercase tracking-wide">
                    Sidearm <span class="text-red-700 dark:text-red-400 ml-1">"鳄鳄"🐊</span>
                </div>
                <div class="text-xs text-neutral-700 dark:text-neutral-300 space-y-2 leading-relaxed flex-grow">
                    <p class="font-bold">带有消音器的魔改近战手枪</p>
                    <ul class="list-square list-inside opacity-90 pl-1">
                        <li>削薄的握把 / 扩大的弹匣井</li>
                        <li>精准的准星</li>
                        <li>将军喜欢叫它"鳄鳄"</li>
                    </ul>
                </div>
                <div class="pt-2 mt-2 border-t border-neutral-300 dark:border-neutral-600 opacity-90 text-xs">
                    <strong>弹药：</strong>常规弹 / 麻醉针
                </div>
            </div>
            <div class="p-4 rounded border border-neutral-300 dark:border-neutral-600 bg-neutral-200/30 dark:bg-neutral-700/30 hover:bg-neutral-200 dark:hover:bg-neutral-700 transition-colors flex flex-col">
                <div class="font-bold text-sm mb-3 text-neutral-900 dark:text-white border-b border-neutral-300 dark:border-neutral-500 pb-2 uppercase tracking-wide">
                    Shotgun
                </div>
                <div class="text-xs text-neutral-700 dark:text-neutral-300 space-y-2 leading-relaxed flex-grow">
                    <p class="font-bold">由普通工兵霰弹枪为原型的魔改霰弹枪</p>
                    <ul class="list-square list-inside opacity-90 pl-1">
                    <li>削断并扩增枪管。后坐力极大。</li>
                    <li>弹药的火药粉中加入一部分月族人骨的骨灰。</li>
                    </ul>
                    <p class="py-1 bg-red-100 dark:bg-red-900/30 px-2 rounded text-red-800 dark:text-red-300 font-bold ">
                    特质：威力巨大,但后坐力也非常人可控.可针对月族士兵造成巨大伤害.
                    </p>
                </div>
                <div class="pt-2 mt-2 border-t border-neutral-300 dark:border-neutral-600 opacity-90 text-xs italic">
                    海准嘉副官:"只有将军能驾驭。"
                </div>
            </div>
            <div class="p-4 rounded border border-neutral-300 dark:border-neutral-600 bg-neutral-200/30 dark:bg-neutral-700/30 hover:bg-neutral-200 dark:hover:bg-neutral-700 transition-colors flex flex-col">
                <div class="font-bold text-sm mb-3 text-neutral-900 dark:text-white border-b border-neutral-300 dark:border-neutral-500 pb-2 uppercase tracking-wide">
                    Carbine
                </div>
                <div class="text-xs text-neutral-700 dark:text-neutral-300 space-y-2 leading-relaxed flex-grow">
                    <p class="font-bold">由军队标配卡宾枪为原型的魔改卡宾枪</p>
                     <ul class="list-square list-inside opacity-90 pl-1">
                    <li>高度模块化,将军可以根据任务需求为其加装下挂榴弹、不同倍率的瞄准镜、各种战术枪托与枪管配件。</li>
                    <li>将军曾用此枪于千里外精准射中敌方高级将领,完成了"未竞的使命".</li>
                    </ul>
                </div>
                <div class="pt-2 mt-2 border-t border-neutral-300 dark:border-neutral-600 opacity-90 text-xs  font-bold italic">
                "the Mission That Never Finished"
                </div>
            </div>
        </div>
        <div class="flex flex-col md:flex-row items-start gap-4 p-4 rounded bg-neutral-200/50 dark:bg-neutral-700/50 border border-neutral-300 dark:border-neutral-600">
            <div class="w-full md:w-auto min-w-[120px]">
                <span class="block text-xs font-bold text-neutral-500 dark:text-neutral-400 uppercase tracking-widest mb-1">Melee / CTM</span>
                <span class="font-bold text-neutral-900 dark:text-white text-base">随身生存匕首</span>
            </div>
            <div class="text-sm text-neutral-700 dark:text-neutral-300 leading-relaxed border-l-0 md:border-l-2 border-neutral-300 dark:border-neutral-500 pl-0 md:pl-4">
                <p class="mb-2">平平无奇，表面上并不具备显著特征，但该战斗方式是将军肉搏战与隐秘作战使用频率最高、稳定性最强的常规战术体系。
                其设计初衷即为与将军自创的 CTM 架构高度兼容，在战斗中可作为 CTM 的主要承载与展开方式。</p>
                <div class="flex flex-wrap items-center gap-2 text-xs">
                    <span class="font-black text-neutral-800 dark:text-neutral-100">CTM 战术体系:</span>
                    <span class="px-2 py-1 bg-neutral-300 dark:bg-neutral-600 rounded text-neutral-800 dark:text-neutral-200 font-medium">瞬间制服</span>
                    <span class="px-2 py-1 bg-neutral-300 dark:bg-neutral-600 rounded text-neutral-800 dark:text-neutral-200 font-medium">审讯</span>
                    <span class="px-2 py-1 bg-neutral-300 dark:bg-neutral-600 rounded text-neutral-800 dark:text-neutral-200 font-medium">无声割喉</span>
                    <span class="px-2 py-1 bg-neutral-300 dark:bg-neutral-600 rounded text-neutral-800 dark:text-neutral-200 font-medium">人体盾牌</span>
                </div>
            </div>
        </div>
    </div>
</div>



