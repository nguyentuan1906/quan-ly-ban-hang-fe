<template>
    <div style="width: 100%; height: 100vh; display: flex; flex-direction: column; justify-content: space-between;">
        <Header />
        <RouterView />
        <Footer />
    </div>
</template>

<script setup lang="ts">
import Header from '../components/layout/Header.vue'
import Footer from '@/components/layout/Footer.vue';

</script>

<style></style>