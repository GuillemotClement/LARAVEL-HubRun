<script setup lang="ts">
const date = new Date();
const year = date.toLocaleString("fr-FR", { year: "numeric" });
</script>
<template>
    <footer class="p-5">
        <p>Copyright &copy; {{ year }}</p>
    </footer>
</template>
