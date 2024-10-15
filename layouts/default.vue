<template>
    <div>
      <UHorizontalNavigation :links="links" class="border-b border-gray-200 dark:border-gray-800" />
      <slot />
    </div>
</template>

<script setup lang="ts">
const links = [
  {
    label: "Home",
    to: "/"
  },
  {
    label: "My book",
    to: "/mybook"
  }
]
</script>