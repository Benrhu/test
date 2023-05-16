<script lang="ts">
import Hero from '@/components/Hero.vue';
import Pricing from '@/components/Pricing.vue';

export default{
  name: '',
  components: {
    Hero,
    Pricing
},
  props: {},
  
}
</script>

<template>
  <Hero />
  <Pricing />
</template>


<route lang="yaml">
meta:
  layout: default
</route>
