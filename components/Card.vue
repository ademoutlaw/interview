<template>
    <div class="card">
        <div class="mx-auto w-1/2">
            <img :src="item.imgUrl" alt="" />
        </div>
        <div class="md:w-1/2">
            <p class="p-3">
                {{ item.text }}
            </p>
        </div>
    </div>
</template>

<script setup lang="ts">
import { defineProps } from "vue";

const { item } = defineProps(["item"]);
</script>

<style scoped>

</style>
