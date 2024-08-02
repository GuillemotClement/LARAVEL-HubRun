<script lang="ts" setup>
import { ref } from "vue";
const name = ref("");
</script>
<template>
    <p>Hello {{ name }}</p>
    <input type="text" v-model="name" class="" />
</template>
