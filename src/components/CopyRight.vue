<template>
    <div class="mx-auto max-w-screen-xl lg:flex lg:items-center lg:justify-between">
        <p>
            Cognignite &copy; 2023
        </p>
    </div>
</template>

<script setup lang="ts">
const VERSION = import.meta.env.VITE_APP_VERSION
const BUILD_DATE = import.meta.env.VITE_APP_BUILD_EPOCH
    ? new Date(Number(import.meta.env.VITE_APP_BUILD_EPOCH))
    : undefined
const thisYear = new Date().getFullYear()
</script>
