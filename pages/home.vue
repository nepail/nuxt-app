<script lang="ts" setup>
	const conuter = useCounter()
</script>

<template>
    <userAvatar></userAvatar>
    <Bar></Bar>
    <div>
        <NuxtLayout name="custom"> home </NuxtLayout>
        <div @click="conuter++">{{ conuter }}</div>
    </div>
</template>