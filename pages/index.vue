

<template>
    <div>
        <div class="hero">
            <div>
                Lorem ipsum dolor sit amet consectetur. Velit aut consequatur
                earum fugiat, aliquid temporibus reiciendis eligendi possimus?
            </div>
        </div>
        <div class="py-4">
            <Card v-for="item in items" :key="item.id" :item="item" />
        </div>
    </div>
</template>

<script setup>
import { ref } from "vue";

const items = ref([
    {
        id: 0,
        imgUrl: "https://placekitten.com/640/360",
        text:
            "Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse reprehenderit cupiditate quae sit. Debitis facere reprehenderit maxime accusantium asperiores nostrum.",
    },
    {
        id: 1,
        imgUrl: "https://placekitten.com/640/360",
        text:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet ipsum itaque eum et sunt velit voluptatem?",
    },
    {
        id: 2,
        imgUrl: "https://placekitten.com/640/360",
        text:
            "Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam facere eligendi reiciendis, optio debitis, sed iste inventore illo, ducimus aut temporibus ab corrupti facilis! Asperiores!",
    },
]);
</script>

<style>

</style>
