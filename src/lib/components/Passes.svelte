<section class="py-24 px-6 max-w-[1400px] mx-auto border-t border-[#1A5C47]/20">
  <h2 class="font-serif text-[clamp(2.5rem,5vw,4rem)] leading-[0.92] font-semibold mb-20 text-[#F5F1E8]">Investment models</h2>

  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <!-- Cards -->
    <div class="lg:col-span-8 grid grid-cols-1 md:grid-cols-2 gap-6">
      
      <!-- Card 1 -->
      <div class="bg-[#1A1F26] p-8 border border-[#1A5C47]/30 flex flex-col h-full relative overflow-hidden group hover:border-[#B8956A]/50 transition-all">
        <div class="flex justify-between items-start mb-6">
          <h3 class="font-serif text-base font-semibold text-[#F5F1E8]">Growth Partnership</h3>
          <span class="bg-[#1A5C47] text-[#F5F1E8] text-[10px] uppercase tracking-wider font-semibold px-2 py-1">25-49%</span>
        </div>
        
        <div class="flex items-baseline gap-2 mb-8">
          <span class="font-serif text-4xl font-semibold text-[#F5F1E8]">$1M-$15M</span>
        </div>

        <p class="text-sm text-[#C5C1B8] mb-8 flex-grow font-light leading-relaxed">
          Strategic capital partnerships where founders remain actively involved. We provide growth capital and operational expertise while you maintain majority control.
        </p>

        <div class="mt-auto">
          <p class="text-xs text-[#C5C1B8] mb-4 font-light">Target: 3+ years old, $3M-$30M revenue, clear path to double-digit margins</p>
          <button class="w-full bg-[#1A5C47] text-[#F5F1E8] py-3 text-sm font-medium border border-[#1A5C47] hover:bg-[#0B3B2D] hover:border-[#B8956A] transition-all">Learn More</button>
        </div>
      </div>

      <!-- Card 2 -->
      <div class="bg-[#1A1F26] p-8 border border-[#1A5C47]/30 flex flex-col h-full relative overflow-hidden group hover:border-[#B8956A]/50 transition-all">
        <div class="flex justify-between items-start mb-6">
          <h3 class="font-serif text-base font-semibold text-[#F5F1E8]">Legacy Buyout</h3>
          <span class="bg-[#1A5C47] text-[#F5F1E8] text-[10px] uppercase tracking-wider font-semibold px-2 py-1">Majority</span>
        </div>
        
        <div class="flex items-baseline gap-2 mb-8">
          <span class="font-serif text-4xl font-semibold text-[#F5F1E8]">$3M-$25M+</span>
        </div>

        <p class="text-sm text-[#C5C1B8] mb-8 flex-grow font-light leading-relaxed">
          Full or majority ownership transitions focused on preserving your legacy. We honor your company's culture, team, and community impact while driving continued growth.
        </p>

        <div class="mt-auto">
          <p class="text-xs text-[#C5C1B8] mb-4 font-light">Target: 3+ years old, $3M-$30M revenue, proven double-digit net margins</p>
          <button class="w-full bg-[#1A5C47] text-[#F5F1E8] py-3 text-sm font-medium border border-[#1A5C47] hover:bg-[#0B3B2D] hover:border-[#B8956A] transition-all">Learn More</button>
        </div>
      </div>

    </div>

    <!-- Included List -->
    <div class="lg:col-span-4 pl-0 lg:pl-12 pt-4">
      <h3 class="font-serif text-sm font-semibold text-[#F5F1E8] mb-6 uppercase tracking-widest">What we bring</h3>
      <ul class="space-y-4">
        {#each ['Strategic capital', 'Operational expertise', 'Elite advisory network', 'M&A experience', 'Long-term commitment', 'Culture preservation', 'Growth acceleration'] as item}
          <li class="text-sm text-[#C5C1B8] flex items-center gap-3 font-light">
             {item}
          </li>
        {/each}
      </ul>
    </div>
  </div>
</section>
