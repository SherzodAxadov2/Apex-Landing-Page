<template>
    <div class="container">
        <div class="otasi">
            <h1 class="nex_1">Features for a better experience</h1>

            <div class="flex">
                <FeatureSingle v-for="(item, index) in features" :key="index" :feature="item" />
            </div>
        </div>
    </div>
</template>
<script setup>
import { ref } from "vue";
import FeatureSingle from "./FeatureSingle.vue";

const features = ref([
    {
        image: 'icon.svg', title: 'Video mesaging', subtitle: `This software is very easy for you to
manage You can use it as you wish ` },
    {
        image: '22.svg', title: 'Save your time', subtitle: `This software is very easy for you to
manage You can use it as you wish ` },
    {
        image: '33.svg', title: 'Keep safe & private', subtitle: `This software is very easy for you to
manage You can use it as you wish ` }
])
</script>
<style scoped>
.nex_1 {
    text-align: center;
    font-size: 50px;
}

img {
    border-radius: 50%;
    height: 70px;
    width: 70px;
}

.parent {
    display: flex;
    justify-content: space-around;
}

.parent h1 {
    font-size: 30px;
}

.otasi {
    margin-top: 50px;
}

.otasi .parent {
    margin-top: 30px;
}

.flex {
    display: flex;
    justify-content: space-between;
}
</style>