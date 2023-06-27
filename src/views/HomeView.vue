<script setup>
import HeaderLandingComponent from '@/components/HeaderLandingComponent.vue'
import MainContentLandingComponent from '@/components/MainContentLandingComponent.vue'
import FooterLandingComponent from '@/components/FooterLandingComponent.vue'
</script>

<template>
  <div class="landing-structure">
    <HeaderLandingComponent class="header-landing-component" />
    <MainContentLandingComponent class="main-content-landing-component" />
    <FooterLandingComponent class="footer-landing-component" />
  </div>
</template>

<style scoped>
.landing-structure {
  display: grid;
  grid-template-areas:
    'landingheader'
    'landingmaincontent'
    'landingfooter';
  gap: 32px;
  /* grid-template-columns: 1fr 1fr 1fr; */
  /* column-gap: 49px; */
  margin: 0 auto;
  padding: 4rem;
  padding-bottom: 120px;
  background: linear-gradient(
    293.29deg,
    #560a27 1.86%,
    #1f1f1f 31.03%,
    #1f1f1f 53.19%,
    #1f1f1f 77.76%,
    #560a27 107.16%
  );
}

.header-landing-component {
  grid-area: landingheader;
}

.main-content-landing-component {
  grid-area: landingmaincontent;
}

.footer-landing-component {
  grid-area: landingfooter;
  height: 100%;
  width: 100%;
}
</style>
