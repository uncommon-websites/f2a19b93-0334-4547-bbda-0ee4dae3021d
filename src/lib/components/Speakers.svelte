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

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200 overflow-hidden" id="leadership">
  <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium mb-8 text-black">Advisory Council</h2>
  
  <p class="text-sm text-gray-600 mb-8 max-w-3xl">Our advisory council comprises current and former C-suite executives from the world's leading financial institutions, providing strategic guidance and ensuring we remain at the forefront of financial advisory and investment solutions.</p>
  
  <div class="border-t border-gray-200">
    {#each advisoryCouncil as advisor}
      <div class="grid grid-cols-1 md:grid-cols-12 py-6 border-b border-gray-200 items-center hover:bg-gray-50 transition-colors cursor-pointer group">
        <div class="md:col-span-4">
          <h3 class="text-xl font-normal text-black">{advisor.name}</h3>
        </div>
        <div class="md:col-span-7">
          <p class="text-xs font-bold text-black mb-0.5">{advisor.company}</p>
          <p class="text-xs text-gray-600">{advisor.role}</p>
        </div>
        <div class="md:col-span-1 flex justify-end opacity-0 group-hover:opacity-100 transition-opacity">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-600"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
        </div>
      </div>
    {/each}
  </div>
</section>
