<script setup>
import HomePage from "./components/HomePage.vue";
</script>

<template>
    <div>
        <a href="#" class="test-link"> Test link </a>
    </div>
    <HomePage msg="Classic Forum Message" />
</template>

<style scoped>
.test-link:hover {
    color: green;
}
</style>
