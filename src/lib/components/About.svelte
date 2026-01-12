<script lang="ts">
  const founderImage = 'https://openstakes.com/wp-content/themes/openstakes_2024/img/main-page/max_1.webp';
</script>

<section class="py-32 px-6 max-w-[1400px] mx-auto border-t border-[#1A5C47]/20" id="about">
  <div class="grid grid-cols-1 lg:grid-cols-12 gap-16 lg:gap-24 items-center">
    <!-- Left: Image -->
    <div class="lg:col-span-5">
      <div class="relative w-full aspect-[3/4] bg-[#1A1F26] overflow-hidden border border-[#1A5C47]/30 group cursor-pointer hover:border-[#B8956A]/50 transition-all duration-500">
        <img 
          src={founderImage} 
          alt="Maximilian Zielinski, Founder & CEO" 
          class="w-full h-full object-cover object-center grayscale group-hover:grayscale-0 transition-all duration-500"
        />
      </div>
    </div>

    <!-- Right: Content -->
    <div class="lg:col-span-7">
      <div class="max-w-2xl">
        <p class="text-xs font-medium text-[#B8956A] mb-4 uppercase tracking-widest">Founder & CEO</p>
        
        <h2 class="font-serif text-[clamp(2.5rem,5vw,4.5rem)] leading-[0.92] tracking-tight font-semibold mb-10 text-[#F5F1E8]">
          Maximilian Zielinski
        </h2>
        
        <div class="space-y-8">
          <p class="text-xl md:text-2xl leading-relaxed text-[#E8E4D9] font-light">
            "I've had the privilege of working alongside some of the world's top enterprising investors. Now, my mission is to bridge the world of high finance with the ambitions of small and medium businesses."
          </p>
          
          <p class="text-base md:text-lg leading-relaxed text-[#C5C1B8] font-light">
            "I want to take what I've learned and make those strategies accessible, helping businesses unlock their potential and drive unprecedented growth."
          </p>
          
          <div class="pt-8 border-t border-[#1A5C47]/30">
            <p class="text-sm text-[#C5C1B8] leading-relaxed font-light">
              Maximilian spent a decade in private equity and family offices serving ultra-wealthy clients. He witnessed how elite financial strategies remained inaccessible to small businesses despite their potential, driving his mission to bridge this gap and level the playing field for SME owners seeking growth capital and strategic exits.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
