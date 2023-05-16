<script lang="ts">
import Hero from '@/components/Hero.vue';
import Features from '@/components/Features.vue'

export default{
  name: '',
  components: {
    Hero,
},
  props: {},
  
}
</script>

<template>
  <Hero />
  <Features />

</template>


<route lang="yaml">
meta:
  layout: default
</route>
