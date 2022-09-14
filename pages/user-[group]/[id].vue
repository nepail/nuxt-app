<template>
    <div>
        user-{{ $route.params.group }} / {{ $route.params.id }}
        <NuxtLink to="/about"> to about</NuxtLink>
        <NuxtLink to="https://www.google.com"> to google</NuxtLink>
    </div>
</template>