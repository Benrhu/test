<script lang="ts">
import About from '@/components/About.vue';
import Content from '@/components/Content.vue';

export default{
  name: '',
  components: {
    About,
    Content
},
  props: {}, 
}
</script>

<template>
  <About />
  <Content />
</template>

<route lang="yaml">
meta:
  layout: default
</route>
