<script lang="ts">
  interface AgendaItemType {
    time: string;
    title?: string;
    subtitle?: string;
    content?: string[];
  }

  export let date = "April 28";
  export let items: AgendaItemType[] = [
    { time: "All day", title: "Pre-conference training (add-on)", subtitle: "Partner Summit (for Stripe partners only)" }
  ];
  export let tags: string[] = [];
</script>

<div class="grid grid-cols-1 lg:grid-cols-12 gap-12 py-12 border-t border-[#1A5C47]/20">
  <!-- Right Content -->
  <div class="lg:col-span-12">
    <div class="flex gap-2 mb-8">
      {#each tags as tag}
        <span class="inline-flex items-center gap-1.5 px-2 py-1 bg-[#1A5C47] text-[10px] font-medium text-[#F5F1E8] uppercase tracking-wide">
          <span class="w-2 h-2 bg-[#B8956A]"></span>
          {tag}
        </span>
      {/each}
    </div>

    <h3 class="font-serif text-3xl font-semibold text-[#F5F1E8] mb-8">{date}</h3>

    <div class="space-y-0">
      {#each items as item}
        <div class="grid grid-cols-1 md:grid-cols-12 py-6 border-t border-[#1A5C47]/20">
          <div class="md:col-span-3">
            <p class="text-sm text-[#B8956A] font-medium uppercase tracking-wider">{item.time}</p>
          </div>
          <div class="md:col-span-9">
             {#if Array.isArray(item.content)}
                <ul class="space-y-1">
                    {#each item.content as line}
                        <li class="text-sm text-[#C5C1B8] font-light">{line}</li>
                    {/each}
                </ul>
             {:else}
                <p class="text-sm text-[#F5F1E8] mb-1 font-medium">{item.title}</p>
                {#if item.subtitle}
                    <p class="text-sm text-[#C5C1B8] font-light">{item.subtitle}</p>
                {/if}
             {/if}
          </div>
        </div>
      {/each}
    </div>
  </div>
</div>
