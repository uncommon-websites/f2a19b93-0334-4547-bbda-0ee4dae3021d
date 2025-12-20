<script lang="ts">
  const founderImage = 'https://openstakes.com/wp-content/themes/openstakes_2024/img/main-page/max_1.webp';
</script>

<section class="py-32 px-6 max-w-[1400px] mx-auto border-t border-gray-200" id="about">
  <div class="grid grid-cols-1 lg:grid-cols-12 gap-16 lg:gap-24 items-center">
    <!-- Left: Image -->
    <div class="lg:col-span-5">
      <div class="relative w-full aspect-[3/4] bg-gray-100 rounded-2xl overflow-hidden border border-gray-200">
        <img 
          src={founderImage} 
          alt="Maximilian Zielinski, Founder & CEO" 
          class="w-full h-full object-cover object-center"
        />
      </div>
    </div>

    <!-- Right: Content -->
    <div class="lg:col-span-7">
      <div class="max-w-2xl">
        <p class="text-sm font-medium text-gray-600 mb-4">Founder & CEO</p>
        
        <h2 class="text-[clamp(2.5rem,5vw,4.5rem)] leading-[0.95] tracking-tight font-medium mb-8 text-[#110F28]">
          Maximilian Zielinski
        </h2>
        
        <div class="space-y-6">
          <p class="text-xl md:text-2xl leading-relaxed text-[#110F28] font-normal">
            "I've had the privilege of working alongside some of the world's top enterprising investors. Now, my mission is to bridge the world of high finance with the ambitions of small and medium businesses."
          </p>
          
          <p class="text-base md:text-lg leading-relaxed text-gray-600">
            "I want to take what I've learned and make those strategies accessible, helping businesses unlock their potential and drive unprecedented growth."
          </p>
          
          <div class="pt-6 border-t border-gray-200">
            <p class="text-sm text-gray-600 leading-relaxed">
              Maximilian spent a decade in private equity and family offices serving ultra-wealthy clients. He witnessed how elite financial strategies remained inaccessible to small businesses despite their potential, driving his mission to bridge this gap and level the playing field for SME owners seeking growth capital and strategic exits.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
