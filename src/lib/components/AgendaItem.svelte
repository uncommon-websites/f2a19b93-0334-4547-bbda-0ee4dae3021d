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

<div class="grid grid-cols-1 lg:grid-cols-12 gap-12 py-12 border-t border-gray-200">
  <!-- Right Content -->
  <div class="lg:col-span-12">
    <div class="flex gap-2 mb-8">
      {#each tags as tag}
        <span class="inline-flex items-center gap-1.5 px-2 py-1 rounded bg-gray-100 text-[10px] font-medium text-gray-700 uppercase tracking-wide">
          <span class="w-2 h-2 rounded-sm bg-black"></span>
          {tag}
        </span>
      {/each}
    </div>

    <h3 class="text-3xl font-medium text-black mb-8">{date}</h3>

    <div class="space-y-0">
      {#each items as item}
        <div class="grid grid-cols-1 md:grid-cols-12 py-6 border-t border-gray-200">
          <div class="md:col-span-3">
            <p class="text-sm text-gray-500 font-medium">{item.time}</p>
          </div>
          <div class="md:col-span-9">
             {#if Array.isArray(item.content)}
                <ul class="space-y-1">
                    {#each item.content as line}
                        <li class="text-sm text-black">{line}</li>
                    {/each}
                </ul>
             {:else}
                <p class="text-sm text-black mb-1">{item.title}</p>
                {#if item.subtitle}
                    <p class="text-sm text-black">{item.subtitle}</p>
                {/if}
             {/if}
          </div>
        </div>
      {/each}
    </div>
  </div>
</div>
