<template >
    <div class="parent">
        <img src="../assets/images/icon.svg" alt="logo">
        <div class="next">
            <h1>{{ feature.title }}</h1>
            <p>{{ feature.subtitle }}</p>
        </div>
    </div>
</template>

<script setup>
defineProps(['feature'])
</script>