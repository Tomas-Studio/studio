<script lang="ts" setup>

useHead({
  htmlAttrs: { lang: 'en', class: 'touch-manipulation' },
  bodyAttrs: { class: 'touch-manipulation antialiased font-sans text-gray-9 dark:text-gray-3' },
  link: [{ rel: 'icon', href: '/to-favicon.png' }],
})

</script>

<template>
  <NuxtRouteAnnouncer>
    <template #default="{ message }">
      <p>{{ message }} was loaded.</p>
    </template>
  </NuxtRouteAnnouncer>
  <NuxtLayout>
    <NuxtPage/>
  </NuxtLayout>
</template>
