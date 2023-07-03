<script setup>
import HeaderLandingComponent from '@/components/HeaderLandingComponent.vue'
import MainContentLandingComponent from '@/components/MainContentLandingComponent.vue'
import FooterLandingComponent from '@/components/FooterLandingComponent.vue'
</script>

<template>
    <div class="landing-structure">
      <HeaderLandingComponent  />
      <MainContentLandingComponent  />
      <FooterLandingComponent  />
    </div>
</template>

<style scoped>
.landing-structure {
  margin: 0 auto;
  padding: 4rem;
  padding-bottom: 120px;
  background: linear-gradient(
    293.29deg,
    #c0c0c0 1.86%,
    #292827 31.03%,
    #292827 53.19%,
    #292827 77.76%,
    #c0c0c0 107.16%
  );
  overflow: hidden;
}

</style>
