<template>
<div class="Home">
    <HeaderShayna/>
    <HelloWorld/>
    <HeroShayna/>
    <Instagram/>
    <PartnherShayna/>
    <FooterShayna/>
</div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue'
import HelloWorld from '@/components/HelloWorld.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import Instagram from '@/components/Instagram.vue'
import PartnherShayna from '@/components/PartnherShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'


export default {
  name: 'Home',
  components: {
   HeaderShayna,
   HelloWorld,
   HeroShayna,
   Instagram,
   PartnherShayna,
   FooterShayna,
  }
};
</script>
