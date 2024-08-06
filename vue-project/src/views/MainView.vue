<template>
<div class="container">
    <Sidebar></Sidebar>
    <div class="content">
        <Router-view></Router-view>
    </div>
</div>
</template>

<script setup>
import { RouterView } from 'vue-router';
import Sidebar from '../components/Sidebar.vue';
</script>

<style>
.container {
    display: flex;
}

.content {
    flex: 1;
    padding: 20px;
}
</style>