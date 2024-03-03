<template>
    <a-row :gutter="[0, 0]">
        <a-col :span="8">
            <RouterLink :to="localPath.home">Home</RouterLink>
        </a-col>
        <a-col :span="8">
            <RouterLink :to="localPath.login">Login</RouterLink>
        </a-col>
        <a-col :span="8">
            img
        </a-col>
    </a-row>
</template>

<script setup lang="ts">
import { localPath } from '@/defined/path';
</script>

<style scoped></style>