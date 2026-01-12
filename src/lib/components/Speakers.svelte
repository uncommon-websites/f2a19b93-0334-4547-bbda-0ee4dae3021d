<script lang="ts">
  const advisoryCouncil = [
    { name: 'Advisory Council Member', role: 'Former C-Suite Executive', company: 'UBS' },
    { name: 'Advisory Council Member', role: 'Former C-Suite Executive', company: 'Deutsche Bank' },
    { name: 'Advisory Council Member', role: 'Former C-Suite Executive', company: 'Citi' },
    { name: 'Advisory Council Member', role: 'Former C-Suite Executive', company: 'Blackstone' },
    { name: 'Advisory Council Member', role: 'Senior Investment Professional', company: 'Multi-Family Office' },
    { name: 'Advisory Council Member', role: 'M&A Specialist', company: 'Investment Banking' }
  ];
</script>

<section class="py-24 px-6 max-w-[1400px] mx-auto border-t border-[#1A5C47]/20 overflow-hidden" id="leadership">
  <h2 class="font-serif text-[clamp(2.5rem,5vw,4rem)] leading-[0.92] font-semibold mb-10 text-[#F5F1E8]">Advisory Council</h2>
  
  <p class="text-sm text-[#C5C1B8] mb-12 max-w-3xl font-light leading-relaxed">Our advisory council comprises current and former C-suite executives from the world's leading financial institutions, providing strategic guidance and ensuring we remain at the forefront of financial advisory and investment solutions.</p>
  
  <div class="border-t border-[#1A5C47]/30">
    {#each advisoryCouncil as advisor}
      <div class="grid grid-cols-1 md:grid-cols-12 py-6 border-b border-[#1A5C47]/20 items-center hover:bg-[#1A1F26] transition-colors cursor-pointer group">
        <div class="md:col-span-4">
          <h3 class="text-xl font-light text-[#F5F1E8]">{advisor.name}</h3>
        </div>
        <div class="md:col-span-7">
          <p class="text-xs font-semibold text-[#B8956A] mb-0.5 uppercase tracking-wider">{advisor.company}</p>
          <p class="text-xs text-[#C5C1B8] font-light">{advisor.role}</p>
        </div>
        <div class="md:col-span-1 flex justify-end opacity-0 group-hover:opacity-100 transition-opacity">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-[#B8956A]"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
        </div>
      </div>
    {/each}
  </div>
</section>
