<script setup>
useHead({
  titleTemplate: (titleChunk) => {
    return titleChunk ? `${titleChunk} - Bintang` : 'Bintang';
  },
  htmlAttrs: {
    lang: 'en'
  },
  meta: [
    { hid: 'description', name: 'description', content: 'Radian is a professional full-stack web developer who had 4+ years of experience and currently pursuing bachelor of computer science. And I love making open-source projects.' }
  ]
})
</script>
<template>
  <div id="app" class="min-h-screen">
    <NuxtLayout>
      <NuxtPage/>
    </NuxtLayout>
  </div>
</template>
