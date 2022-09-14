<script lang="ts" setup>
const conuter  = useCounter()
// console.log(useDark)
</script>

<template>
    <div>
        <!-- <NuxtWelcome /> -->
        index
        <div @click="conuter ++">{{ conuter  }}</div>
        <NuxtLink to="/home">to home</NuxtLink>
    </div>
</template>
