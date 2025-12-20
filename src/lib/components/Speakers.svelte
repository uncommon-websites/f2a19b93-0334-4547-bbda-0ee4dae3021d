<script lang="ts">
  import { ArrowLeft, ArrowRight } from 'lucide-svelte';

  const featuredLeader = [
    { name: 'Maximilian Zielinski', role: 'Founder & CEO', img: 'https://openstakes.com/wp-content/themes/openstakes_2024/img/main-page/max_1.webp' }
  ];

  const advisoryCouncil = [
    { name: 'Advisory Council Member', role: 'Former C-Suite Executive', company: 'UBS' },
    { name: 'Advisory Council Member', role: 'Former C-Suite Executive', company: 'Deutsche Bank' },
    { name: 'Advisory Council Member', role: 'Former C-Suite Executive', company: 'Citi' },
    { name: 'Advisory Council Member', role: 'Former C-Suite Executive', company: 'Blackstone' },
    { name: 'Advisory Council Member', role: 'Senior Investment Professional', company: 'Multi-Family Office' },
    { name: 'Advisory Council Member', role: 'M&A Specialist', company: 'Investment Banking' }
  ];
</script>

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200 overflow-hidden" id="about">
  <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium mb-8 text-[#110F28]">Leadership</h2>
  
  <p class="text-sm font-medium text-gray-600 mb-6">Founder</p>

  <!-- Featured Leader -->
  <div class="relative w-full pb-12">
    <div class="flex gap-6">
      {#each featuredLeader as leader}
        <div class="w-full max-w-[420px] bg-white rounded-lg overflow-hidden shadow-sm group cursor-pointer relative flex flex-col h-[520px] border border-gray-100 transition-all hover:shadow-md">
            <!-- Top Section with Name and Image -->
            <div class="relative flex-grow bg-gray-50 overflow-hidden">
                <!-- Name -->
                <div class="absolute top-6 left-6 z-10">
                    <h3 class="text-3xl font-medium text-[#110F28] leading-[0.9] tracking-tight">
                        {#each leader.name.split(' ') as word}
                            <div>{word}</div>
                        {/each}
                    </h3>
                </div>
                
                <!-- Image -->
                <img 
                    src={leader.img} 
                    alt={leader.name} 
                    class="absolute bottom-0 right-0 w-[85%] h-auto object-cover object-bottom transition-all duration-500" 
                />
            </div>

            <!-- Bottom Section with Role -->
            <div class="p-6 bg-white border-t border-gray-100 relative">
                <p class="text-xs font-bold text-[#110F28] mb-1">Openstakes</p>
                <p class="text-xs text-gray-600 mb-3">{leader.role}</p>
                <p class="text-xs text-gray-600 leading-relaxed">Maximilian spent a decade in private equity and family offices serving ultra-wealthy clients. He witnessed how elite financial strategies remained inaccessible to small businesses despite their potential, driving his mission to bridge this gap.</p>
                
                <!-- Arrow Icon -->
                <div class="absolute bottom-6 right-6 opacity-0 group-hover:opacity-100 transition-opacity">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-[#110F28]"><path d="M7 17L17 7"></path><path d="M7 7h10v10"></path></svg>
                </div>
            </div>
        </div>
      {/each}
    </div>
  </div>

  <!-- Advisory Council List -->
  <div>
    <p class="text-sm font-medium text-gray-600 mb-6">Esteemed Advisory Council</p>
    <p class="text-sm text-gray-600 mb-6 max-w-3xl">Our advisory council comprises current and former C-suite executives from the world's leading financial institutions, providing strategic guidance and ensuring we remain at the forefront of financial advisory and investment solutions.</p>
    <div class="border-t border-gray-200">
      {#each advisoryCouncil as advisor}
        <div class="grid grid-cols-1 md:grid-cols-12 py-4 border-b border-gray-200 items-center hover:bg-gray-50 transition-colors cursor-pointer group">
          <div class="md:col-span-4">
            <h3 class="text-xl font-normal text-[#110F28]">{advisor.name}</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-xs font-bold text-[#110F28] mb-0.5">{advisor.company}</p>
            <p class="text-xs text-gray-600">{advisor.role}</p>
          </div>
          <div class="md:col-span-1 flex justify-end opacity-0 group-hover:opacity-100 transition-opacity">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-400"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
          </div>
        </div>
      {/each}
    </div>
  </div>

</section>

<style>
  .hide-scrollbar::-webkit-scrollbar {
    display: none;
  }
  .hide-scrollbar {
    -ms-overflow-style: none;
    scrollbar-width: none;
  }
</style>
