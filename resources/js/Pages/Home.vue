<script setup>
    import { ref } from "vue";

    const count = ref(0)
</script>

<template>
    <div>
        <h1>Home Page</h1>
        <div>
            {{ count }}
            <button @click="count++">
                Add
            </button>
        </div>
    </div>
</template>

<style scoped>

</style>
