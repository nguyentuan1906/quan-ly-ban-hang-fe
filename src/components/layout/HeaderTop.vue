<template>
    <div class="header">
        <a-button>
            Theo dõi đơn hàng
        </a-button>
        <a-button>
            Trợ giúp
        </a-button>
    </div>
</template>

<script setup lang="ts">
import { Button } from 'ant-design-vue';

</script>

<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    padding: 0px 100px;
    height: 40px
}
button {
    border: none;
}
</style>