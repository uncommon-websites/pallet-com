<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Logos from "$lib/components/Logos.svelte";
  import FeatureHeader from "$lib/components/FeatureHeader.svelte";
  import FeatureGrid from "$lib/components/FeatureGrid.svelte";
  import ComparisonChart from "$lib/components/ComparisonChart.svelte";
  import BentoGrid from "$lib/components/BentoGrid.svelte";
  import NewsSection from "$lib/components/NewsSection.svelte";
  import CTA from "$lib/components/CTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<main class="bg-[#050505] min-h-screen text-white selection:bg-red-500/30">
  <Navbar />
  <Hero />
  <Logos />
  <FeatureHeader />
  <FeatureGrid />
  <ComparisonChart />
  <BentoGrid />
  <NewsSection />
  <CTA />
  <Footer />
</main>

