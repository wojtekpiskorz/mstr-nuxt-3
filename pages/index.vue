<template>
  <NuxtLink
    class="underline font-medium"
    :href="firstLesson.path"
  >
    Go to first lessonss
  </NuxtLink>
</template>

<script setup lang="ts">
const firstLesson = await useFirstLesson();
</script>
