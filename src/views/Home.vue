<template>
  <div class="home">
      <headerShayna/>
      <heroSection/>
      <womenBanner/>
      <instaShayna/>
      <logoPartner/>
      <footerShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
import headerShayna from '@/components/HeaderShayna.vue'
import womenBanner from '@/components/WomenBanner.vue'
import HeroSection from '@/components/HeroSection.vue'
import instaShayna from '@/components/InstaShayna.vue'
import logoPartner from '@/components/LogoPartner.vue'
import footerShayna from '@/components/FooterShayna.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    headerShayna,
    womenBanner,
    instaShayna,
    logoPartner,
    footerShayna,
    HeroSection
  }
}
</script>
