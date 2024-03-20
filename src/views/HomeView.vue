<template>
  <div class="home">
    <HeaderSection />
    <HeroSection />
    <BannerSection />
    <InstagramSection />
    <LogoPartnerSection />
    <FooterSection />
  </div>
</template>

<script>
// @ is an alias to /src

import HeaderSection from "@/components/HeaderSection.vue";
import HeroSection from "@/components/HeroSection.vue";
import BannerSection from "@/components/BannerSection.vue";
import InstagramSection from "@/components/InstagramSection.vue";
import LogoPartnerSection from "@/components/LogoPartnerSection.vue";
import FooterSection from "@/components/FooterSection.vue";

export default {
  name: "HomeView",
  components: {
    HeaderSection,
    HeroSection,
    BannerSection,
    InstagramSection,
    LogoPartnerSection,
    FooterSection,
  },
};
</script>../components/InstagramSection.vue../components/HeroMia.vue
