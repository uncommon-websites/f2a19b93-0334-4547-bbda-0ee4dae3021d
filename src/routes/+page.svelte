<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import WhyAttend from "$lib/components/WhyAttend.svelte";
  import Passes from "$lib/components/Passes.svelte";
  import Speakers from "$lib/components/Speakers.svelte";
  import Agenda from "$lib/components/Agenda.svelte";
  import Sponsors from "$lib/components/Sponsors.svelte";
  import FAQ from "$lib/components/FAQ.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<svelte:head>
  <title>Openstakes - Bridging Institutional Finance with SME Ambitions</title>
  <meta name="description" content="Openstakes democratizes elite financial strategies for small and medium businesses through strategic capital partnerships and hands-on advisory. Based in Brisbane & Gold Coast, Queensland." />
  <meta property="og:title" content="Openstakes - Bridging Institutional Finance with SME Ambitions" />
  <meta property="og:description" content="Strategic capital partnerships and corporate advisory for Australian SME businesses seeking growth capital and strategic exits." />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary_large_image" />
</svelte:head>

<main class="bg-[#F7F7F8] min-h-screen font-sans text-[#110F28] selection:bg-primary-600 selection:text-white">
  <Header />
  <Hero />
  <WhyAttend />
  <Passes />
  <Speakers />
  <Agenda />
  <Sponsors />
  <FAQ />
  <Footer />
</main>

