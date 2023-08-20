<script setup>
        const props = defineProps(['image']);
</script>

<template>
        <img :src="image" class="profile" alt="profile"/>
</template>