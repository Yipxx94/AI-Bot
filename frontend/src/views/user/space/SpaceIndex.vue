<script setup>
import {useRoute} from "vue-router";

// 调用当前页面参数
const route = useRoute();

</script>

<template>
个人空间: {{ route.params.user_id }}
</template>

<style scoped>

</style>