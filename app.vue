<template>
  <div>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">

useHead
  ({
    title: 'My App',
    meta: [
      {
        name: 'description',
        content: 'My amazing site.'
      }
    ],
    bodyAttrs: {
      class: 'test'
    },
    script: [{}]
  })
</script>
