<script lang="ts">
  import { Play } from 'lucide-svelte';
</script>

<section class="pt-32 pb-24 px-6 max-w-[1400px] mx-auto relative">
  <!-- Subtle architectural line work -->
  <div class="absolute top-0 right-0 w-96 h-96 opacity-5 pointer-events-none">
    <svg viewBox="0 0 400 400" fill="none" xmlns="http://www.w3.org/2000/svg">
      <line x1="0" y1="100" x2="400" y2="100" stroke="#1A5C47" stroke-width="1"/>
      <line x1="0" y1="200" x2="400" y2="200" stroke="#1A5C47" stroke-width="1"/>
      <line x1="0" y1="300" x2="400" y2="300" stroke="#1A5C47" stroke-width="1"/>
      <line x1="100" y1="0" x2="100" y2="400" stroke="#1A5C47" stroke-width="1"/>
      <line x1="200" y1="0" x2="200" y2="400" stroke="#1A5C47" stroke-width="1"/>
      <line x1="300" y1="0" x2="300" y2="400" stroke="#1A5C47" stroke-width="1"/>
    </svg>
  </div>

  <h1 class="font-serif text-[clamp(3rem,8vw,6.5rem)] leading-[0.92] tracking-tight font-semibold max-w-4xl mb-16 text-[#F5F1E8]">
    Bridging institutional finance with SME ambitions
  </h1>

  <div class="flex flex-col md:flex-row gap-8 md:gap-32 mb-20 text-sm font-medium text-[#C5C1B8] uppercase tracking-wider">
    <div>
      <p>Strategic Capital</p>
      <p>Partnerships</p>
    </div>
    <div>
      <p>Brisbane & Gold Coast,</p>
      <p>Queensland</p>
    </div>
  </div>

  <!-- Video Placeholder -->
  <div class="mb-24 w-full">
    <div class="relative w-full aspect-video bg-gradient-to-br from-[#1A1F26] to-[#0B3B2D] overflow-hidden group cursor-pointer border border-[#1A5C47]/30 hover:border-[#B8956A]/50 transition-all duration-500">
      <!-- Subtle texture overlay -->
      <div class="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNjAiIGhlaWdodD0iNjAiIHZpZXdCb3g9IjAgMCA2MCA2MCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxwYXRoIGQ9Ik0zNiAxOGMzLjMxNCAwIDYgMi42ODYgNiA2cy0yLjY4NiA2LTYgNi02LTIuNjg2LTYtNiAyLjY4Ni02IDYtNnoiIHN0cm9rZT0iIzFBNUM0NyIgc3Ryb2tlLXdpZHRoPSIuNSIgb3BhY2l0eT0iLjEiLz48L2c+PC9zdmc+')] opacity-30"></div>
      
      <!-- Watch Video button -->
      <div class="absolute inset-0 flex items-center justify-center">
        <div class="flex items-center gap-4 px-10 py-5 bg-[#1A5C47] border border-[#B8956A]/30 backdrop-blur-sm transition-all group-hover:bg-[#0B3B2D] group-hover:border-[#B8956A]">
          <Play class="w-6 h-6 text-[#F5F1E8] fill-[#F5F1E8]" />
          <span class="text-[#F5F1E8] text-base font-medium tracking-wide">Watch Video</span>
        </div>
      </div>
    </div>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-12 gap-6">
    <div class="md:col-start-7 md:col-span-6 lg:col-start-7 lg:col-span-5">
      <p class="text-xl md:text-2xl leading-relaxed text-[#E8E4D9] font-light">
        In an open stakes game of poker, the player with the largest bank roll has an unfair advantage. The same is true in the world of business. <span class="font-medium text-[#B8956A] border-b border-[#B8956A]/50">We democratize elite financial strategies</span> for small and medium businesses seeking growth capital and strategic exits.
      </p>
    </div>
  </div>
</section>
