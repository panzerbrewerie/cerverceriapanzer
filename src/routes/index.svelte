<script>
  import HeroBanner from '../components/HeroBanner.svelte';
  import Overview from '../components/Overview.svelte';
  import OpenHours from '../components/OpenHours.svelte';
</script>

<style>

</style>

<svelte:head>
  <title>NerdCafé</title>
</svelte:head>

<div>
  <HeroBanner
    bannerTitle="Cerveza Panzer"
    bannerSubtitle="Tomate la Animal IPA en un suanfonson"
    themeBannerFullHeight
    bannerImg="homepage" />
  <Overview />
  <OpenHours />
</div>
