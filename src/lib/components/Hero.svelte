<script lang="ts">
  import { Play } from 'lucide-svelte';
</script>

<section class="pt-32 pb-20 px-6 max-w-[1400px] mx-auto">
  <h1 class="text-[clamp(3rem,8vw,6.5rem)] leading-[0.95] tracking-tight font-medium max-w-4xl mb-12 text-black">
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
    <div class="relative w-full aspect-video bg-gradient-to-br from-gray-200 to-gray-300 rounded-2xl overflow-hidden group cursor-pointer border border-gray-300 grayscale hover:grayscale-0 transition-all duration-500">
      <!-- Subtle overlay -->
      <div class="absolute inset-0 bg-black/5"></div>
      
      <!-- Watch Video button with dark overlay -->
      <div class="absolute inset-0 flex items-center justify-center">
        <div class="flex items-center gap-3 px-8 py-4 bg-black/60 backdrop-blur-sm rounded-lg transition-all group-hover:bg-black/70">
          <Play class="w-6 h-6 text-white fill-white" />
          <span class="text-white text-lg font-medium">Watch Video</span>
        </div>
      </div>
    </div>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-12 gap-6">
    <div class="md:col-start-7 md:col-span-6 lg:col-start-7 lg:col-span-5">
      <p class="text-xl md:text-2xl leading-snug text-black font-normal">
        In an open stakes game of poker, the player with the largest bank roll has an unfair advantage. The same is true in the world of business. <span class="font-medium border-b-2 border-black">We democratize elite financial strategies</span> for small and medium businesses seeking growth capital and strategic exits.
      </p>
    </div>
  </div>
</section>
