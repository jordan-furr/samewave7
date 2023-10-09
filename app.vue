<script setup lang="ts">

useHead({
  title: 'Samewave 7',
  meta: [
    { name: 'description', content: 'Fiber art by Katrina Stalcup and Jordan Furr'},
    { name: 'theme-color', content: '#4285f4'}
  ],
  bodyAttrs: {
    class: 'test'
  },
  script: [ { innerHTML: 'console.log(\'Hello world\')' } ]
})

useSeoMeta({
  title: 'Samewave7',
  ogTitle: 'Samewave7',
  description: 'Fiber art by Katrina Stalcup and Jordan Furr',
  ogDescription: 'Fiber art by Katrina Stalcup and Jordan Furr',
  ogImage: '/public/stitch_logo',
  twitterCard: 'summary_large_image',
})
</script>

<template>
  <div>
    <NuxtPage />
  </div>
</template>