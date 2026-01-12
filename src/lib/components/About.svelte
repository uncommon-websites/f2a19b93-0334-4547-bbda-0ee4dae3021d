<script lang="ts">
  const founderImage = 'https://openstakes.com/wp-content/themes/openstakes_2024/img/main-page/max_1.webp';
</script>

<section class="py-40 px-12 max-w-[1600px] mx-auto border-t border-[#FAFAF8]/5" id="about">
  <div class="grid grid-cols-1 lg:grid-cols-12 gap-24 lg:gap-32 items-start">
    <!-- Left: Image -->
    <div class="lg:col-span-5">
      <div class="relative w-full aspect-[3/4] bg-[#0F0F0F] overflow-hidden border border-[#FAFAF8]/5 group cursor-pointer hover:border-[#004225]/50 transition-all duration-500">
        <img 
          src={founderImage} 
          alt="Maximilian Zielinski, Founder & CEO" 
          class="w-full h-full object-cover object-center grayscale group-hover:grayscale-0 transition-all duration-700"
        />
      </div>
    </div>

    <!-- Right: Content -->
    <div class="lg:col-span-7">
      <div class="max-w-2xl">
        <p class="text-[11px] font-medium text-[#004225] mb-6 uppercase tracking-[0.2em]">Founder & CEO</p>
        
        <h2 class="font-serif text-[clamp(3rem,6vw,5rem)] leading-[0.9] tracking-tight font-semibold mb-16 text-[#FAFAF8]">
          Maximilian Zielinski
        </h2>
        
        <div class="space-y-12">
          <p class="text-[22px] leading-[1.7] text-[#F5F5F0] font-light">
            I've had the privilege of working alongside some of the world's top enterprising investors. Now, my mission is to bridge the world of high finance with the ambitions of small and medium businesses.
          </p>
          
          <p class="text-[18px] leading-[1.7] text-[#C5C1B8] font-light">
            Maximilian spent a decade in private equity and family offices serving ultra-wealthy clients. He witnessed how elite financial strategies remained inaccessible to small businesses despite their potential, driving his mission to bridge this gap and level the playing field for SME owners seeking growth capital and strategic exits.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
