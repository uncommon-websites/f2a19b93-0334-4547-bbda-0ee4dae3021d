<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200">
  <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium mb-16 text-[#110F28]">Investment models</h2>

  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <!-- Cards -->
    <div class="lg:col-span-8 grid grid-cols-1 md:grid-cols-2 gap-6">
      
      <!-- Card 1 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col h-full relative overflow-hidden group hover:shadow-md transition-shadow">
        <div class="flex justify-between items-start mb-6">
          <h3 class="text-sm font-medium text-gray-900">Growth Partnership</h3>
          <span class="bg-gray-100 text-gray-600 text-[10px] uppercase tracking-wider font-semibold px-2 py-1 rounded">25-49%</span>
        </div>
        
        <div class="flex items-baseline gap-2 mb-8">
          <span class="text-4xl font-medium text-[#110F28]">$1M-$15M</span>
        </div>

        <p class="text-sm text-gray-600 mb-8 flex-grow">
          Strategic capital partnerships where founders remain actively involved. We provide growth capital and operational expertise while you maintain majority control.
        </p>

        <div class="mt-auto">
          <p class="text-xs text-gray-500 mb-4">Target: 3+ years old, $3M-$30M revenue, clear path to double-digit margins</p>
          <button class="w-full bg-[#110F28] text-white py-3 rounded-full text-sm font-medium hover:bg-opacity-90 transition-opacity">Learn More</button>
        </div>
      </div>

      <!-- Card 2 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col h-full relative overflow-hidden group hover:shadow-md transition-shadow">
        <div class="flex justify-between items-start mb-6">
          <h3 class="text-sm font-medium text-gray-900">Legacy Buyout</h3>
          <span class="bg-gray-100 text-gray-600 text-[10px] uppercase tracking-wider font-semibold px-2 py-1 rounded">Majority</span>
        </div>
        
        <div class="flex items-baseline gap-2 mb-8">
          <span class="text-4xl font-medium text-[#110F28]">$3M-$25M+</span>
        </div>

        <p class="text-sm text-gray-600 mb-8 flex-grow">
          Full or majority ownership transitions focused on preserving your legacy. We honor your company's culture, team, and community impact while driving continued growth.
        </p>

        <div class="mt-auto">
          <p class="text-xs text-gray-500 mb-4">Target: 3+ years old, $3M-$30M revenue, proven double-digit net margins</p>
          <button class="w-full bg-[#110F28] text-white py-3 rounded-full text-sm font-medium hover:bg-opacity-90 transition-opacity">Learn More</button>
        </div>
      </div>

    </div>

    <!-- Included List -->
    <div class="lg:col-span-4 pl-0 lg:pl-12 pt-4">
      <h3 class="text-sm font-medium text-[#110F28] mb-6">What we bring</h3>
      <ul class="space-y-4">
        {#each ['Strategic capital', 'Operational expertise', 'Elite advisory network', 'M&A experience', 'Long-term commitment', 'Culture preservation', 'Growth acceleration'] as item}
          <li class="text-sm text-gray-600 flex items-center gap-3">
             {item}
          </li>
        {/each}
      </ul>
    </div>
  </div>
</section>
