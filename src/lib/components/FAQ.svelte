<script lang="ts">
  import { Plus } from 'lucide-svelte';

  const faqs = [
    "What types of businesses does Openstakes invest in?",
    "How does the Growth Partnership model work?",
    "What is the difference between Growth Partnership and Legacy Buyout?",
    "Will my company's culture and team be preserved?",
    "What is the typical investment timeline?",
    "How involved will Openstakes be in day-to-day operations?",
    "What industries do you focus on?",
    "How do I know if my business is ready for a partnership?",
    "What is the 'no-arseholes policy'?",
    "How can I get in touch to discuss a potential partnership?"
  ];
</script>

<section class="py-24 px-6 max-w-[1400px] mx-auto border-t border-[#1A5C47]/20" id="faq">
  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-4">
      <h2 class="font-serif text-[clamp(2.5rem,5vw,4rem)] leading-[0.92] font-semibold text-[#F5F1E8]">FAQs</h2>
    </div>

    <div class="lg:col-span-8">
      <div class="border-t border-[#1A5C47]/30">
        {#each faqs as question}
          <div class="py-5 border-b border-[#1A5C47]/20 flex justify-between items-center cursor-pointer group hover:bg-[#1A1F26] transition-colors px-2 -mx-2">
            <h3 class="text-sm font-medium text-[#F5F1E8] pr-8 font-light">{question}</h3>
            <div class="text-[#B8956A] group-hover:text-[#F5F1E8] transition-colors">
              <Plus size={16} />
            </div>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
