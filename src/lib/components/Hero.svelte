<script lang="ts">
  import { Play } from 'lucide-svelte';
</script>

<section class="pt-32 pb-20 px-6 max-w-[1400px] mx-auto">
  <h1 class="text-[clamp(3rem,8vw,6.5rem)] leading-[0.95] tracking-tight font-medium max-w-4xl mb-12 text-[#110F28]">
    Bridging institutional finance with SME ambitions
  </h1>

  <div class="flex flex-col md:flex-row gap-8 md:gap-32 mb-16 text-sm font-medium text-gray-600">
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
  <div class="mb-20 w-full">
    <div class="relative w-full aspect-video bg-gradient-to-br from-gray-200 to-gray-300 rounded-2xl overflow-hidden group cursor-pointer border border-gray-300">
      <!-- Subtle overlay -->
      <div class="absolute inset-0 bg-black/5"></div>
      
      <!-- Play button -->
      <div class="absolute inset-0 flex items-center justify-center">
        <div class="w-20 h-20 bg-white/90 backdrop-blur-sm rounded-full flex items-center justify-center transition-all group-hover:scale-110 group-hover:bg-white border border-gray-200">
          <Play class="w-8 h-8 text-[#110F28] ml-1" />
        </div>
      </div>
      
      <!-- Watch Video text -->
      <div class="absolute inset-0 flex items-center justify-center pointer-events-none">
        <div class="text-center mt-32">
          <p class="text-sm font-medium text-gray-700 opacity-0 group-hover:opacity-100 transition-opacity">Watch Video</p>
        </div>
      </div>
    </div>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-12 gap-6">
    <div class="md:col-start-7 md:col-span-6 lg:col-start-7 lg:col-span-5">
      <p class="text-xl md:text-2xl leading-snug text-white font-normal">
        In an open stakes game of poker, the player with the largest bank roll has an unfair advantage. The same is true in the world of business. We democratize elite financial strategies for small and medium businesses seeking growth capital and strategic exits.
      </p>
    </div>
  </div>
</section>
