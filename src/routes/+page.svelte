<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Expertise from "$lib/components/Expertise.svelte";
  import About from "$lib/components/About.svelte";
  import WhyAttend from "$lib/components/WhyAttend.svelte";
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

<main class="bg-[#0B0E13] min-h-screen font-sans text-[#F8F9FA] selection:bg-[#C5A572] selection:text-[#0B0E13]">
  <Header />
  <Hero />
  <Expertise />
  <About />
  <WhyAttend />
  <Footer />
</main>

