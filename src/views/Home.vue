<template>
  <div class="home">
      
    <HeaderBoons/>
    <HeroBoons />
    <WomenBoons />
    <InstaBoons />
    <PartnerBoons />
    <FooterBoons />
  </div>
</template>

<script>

import HeaderBoons from "@/components/HeaderBoons.vue";
import HeroBoons from "@/components/HeroBoons.vue";
import WomenBoons from "@/components/WomenBoons.vue";
import InstaBoons from "@/components/InstaBoons.vue";
import PartnerBoons from "@/components/PartnerBoons.vue";
import FooterBoons from "@/components/FooterBoons.vue";



export default {
  name: "Home",
  components: {
    HeaderBoons,
    HeroBoons,
    WomenBoons,
    InstaBoons,
    PartnerBoons,
    FooterBoons
  }
}
</script>
