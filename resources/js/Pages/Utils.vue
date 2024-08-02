<script lang="ts" setup>
import Header from "@/Layouts/Header.vue";
import { Head, Link } from "@inertiajs/vue3";

import { ref } from "vue";
const name = ref("");
</script>
<template>
    <Head title="HubRun" />
    <Header />
    <div class="container mx-auto min-h-screen border border-red-500">
        <p>Hello {{ name }}</p>
        <input type="text" v-model="name" class="rounded-xl" />
    </div>
</template>
