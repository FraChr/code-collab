<script setup lang="ts">
    defineProps<{
        appName: string; year: number
    }>()
</script>

<template>
    <footer>{{ appName }} &copy; {{ year }}</footer>
</template>