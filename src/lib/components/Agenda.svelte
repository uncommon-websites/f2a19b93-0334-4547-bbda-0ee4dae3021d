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

<section class="px-6 max-w-[1400px] mx-auto" id="portfolio">
  <AgendaItem {...portfolio} />
  <AgendaItem {...transactions} />
  <AgendaItem {...exits} />
</section>
