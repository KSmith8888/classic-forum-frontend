<script setup>
import { ref } from "vue";

defineProps({
    msg: String,
});

const count = ref(0);
</script>

<template>
    <h1>{{ msg }}</h1>

    <div class="card">
        <button type="button" @click="count++">count is {{ count }}</button>
        <p>This is the HomePage component</p>
    </div>

    <p>This is the test paragraph</p>
</template>

<style scoped>
.test {
    color: #888;
}
</style>
