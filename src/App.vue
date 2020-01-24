<template>
  <div id="app">
    <brand-nav />
    <p-carousel />
    <content-tabs />
  </div>
</template>

<script>
import BrandNav from "@/components/BrandNav";
import PCarousel from "@/components/PCarousel";
import ContentTabs from "@/components/ContentTabs";
export default {
  name: "app",
  components: { BrandNav, PCarousel, ContentTabs }
};
</script>
