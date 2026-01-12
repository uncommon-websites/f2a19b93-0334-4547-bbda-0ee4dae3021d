<script lang="ts">
  import AgendaItem from './AgendaItem.svelte';

  const portfolio = {
    date: "Active Portfolio",
    tags: ["Holdings"],
    items: [
      { time: "Construction", title: "Factor Constructions", subtitle: "General contracting and luxury house building firm in Queensland" },
      { time: "Media", title: "Focl Media", subtitle: "Media production house experiencing significant growth in client base and production capabilities" },
      { time: "Design", title: "Focl Design", subtitle: "Building design firm offering architectural design services" }
    ]
  };

  const transactions = {
    date: "Notable Transactions",
    tags: ["Advisory"],
    items: [
      { time: "Feb 2025", content: ["Appointed exclusive financial advisors (with Maecenas)", "$350M Greendale Village mixed-use development in Brisbane"] },
      { time: "Mar 2024", content: ["Facilitated exclusive agreement for MAYD Group", "$400M Kirra Hotel and Residences project"] },
      { time: "Nov 2023", content: ["Successfully raised first stage funding", "Goldberg Developments flagship townhouse development in Hope Island"] },
      { time: "Sep 2023", content: ["Secured $40M in funding", "Goldberg Developments townhouse project"] },
      { time: "Jun 2023", content: ["Facilitated $16M refinancing", "One Burleigh Tower site with LEDA"] }
    ]
  };

  const exits = {
    date: "Successful Exits",
    tags: ["Track Record"],
    items: [
      { time: "2024", title: "International Coffee Company", subtitle: "Australian franchise - Successfully divested after substantial growth in market presence and profitability" }
    ]
  };
</script>

<section class="px-6 max-w-[1400px] mx-auto border-t border-[#1A5C47]/20" id="portfolio">
  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 pt-24">
    <!-- Sticky Left Header -->
    <div class="lg:col-span-5 lg:sticky lg:top-24 lg:self-start">
      <h2 class="font-serif text-[clamp(2.5rem,5vw,4rem)] leading-[0.92] font-semibold mb-10 text-[#F5F1E8]">Portfolio &<br>track record</h2>
      <button class="bg-[#1A5C47] text-[#F5F1E8] text-xs font-medium px-6 py-3 border border-[#1A5C47] hover:bg-[#0B3B2D] hover:border-[#B8956A] transition-all">
        Partner With Us
      </button>
    </div>

    <!-- Right Content Area -->
    <div class="lg:col-span-7">
      <AgendaItem {...portfolio} />
      <AgendaItem {...transactions} />
      <AgendaItem {...exits} />
    </div>
  </div>
</section>
