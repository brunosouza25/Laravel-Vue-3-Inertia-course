<template>
        <div>Index</div>
        <Link href="/hello">Show Page</Link>
</template>

<script setup>
import { Link } from '@inertiajs/inertia-vue3'
import MainLayout from "../../Layouts/MainLayout.vue";
defineProps({
    message: String
})
</script>
