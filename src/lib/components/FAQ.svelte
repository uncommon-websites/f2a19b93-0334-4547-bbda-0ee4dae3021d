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

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-800" id="faq">
  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-4">
      <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium text-white">FAQs</h2>
    </div>

    <div class="lg:col-span-8">
      <div class="border-t border-gray-800">
        {#each faqs as question}
          <div class="py-5 border-b border-gray-800 flex justify-between items-center cursor-pointer group hover:bg-gray-900 transition-colors px-2 -mx-2 rounded-sm">
            <h3 class="text-sm font-medium text-white pr-8">{question}</h3>
            <div class="text-gray-400 group-hover:text-white transition-colors">
              <Plus size={16} />
            </div>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
