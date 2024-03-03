<template>
    <div style="display: flex; justify-content: center; align-items: center;">
        <a-row :gutter="[16, 16]" style="width: 30%;">
            <a-col :span="24" style="display: flex; justify-content: center; align-items: center;">
                <h1>Đăng nhập</h1>
            </a-col>
            <a-col :span="24">
                <a-input size="large" placeholder="large size" />
            </a-col>
            <a-col :span="24">
                <a-input size="large" placeholder="large size" />
            </a-col>
            <a-col :span="24" style="display: flex; justify-content: space-between;">
                <RouterLink to="/">Đăng ký tài khoản</RouterLink>
                <RouterLink to="/about">Quên mật khẩu</RouterLink>
            </a-col>
            <a-col :span="24">
                <a-button style="width: 100%; height: 40px;">Đăng nhập</a-button>
            </a-col>
        </a-row>
    </div>
</template>

<script setup lang="ts">
import apiUrl from '@/defined';

console.log(import.meta.env.BASE_URL);
console.log('api', apiUrl);
</script>
