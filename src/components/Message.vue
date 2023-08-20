<script setup>
    const props = defineProps(['message']);
</script>

<template>
    <p class="message"> {{ message }} </p>
</template>