<template>
  <NuxtLink
    class="underline font-medium"
    :href="firstLesson.path"
  >
    Go to first lessons
  </NuxtLink>
</template>

<script setup lang="ts">
const firstLesson = await useFirstLesson();
</script>
