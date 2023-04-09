<script setup lang="ts">
    defineProps<{
        name: string
    }>();
</script>

<template>
    <div class="customer">
        <h1>{{ name }}</h1>
    </div>
</template>