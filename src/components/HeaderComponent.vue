<script setup>
import { RouterLink } from 'vue-router';
import { CoHamburgerMenu } from "oh-vue-icons/icons";
</script>

<template>
    <nav class="flex flex-row justify-around py-4 px-6 bg-slate-100 shadow-md mb-3 items-center gap-5">
        <span>
            <CoHamburgerMenu />
        </span>
        <RouterLink to="/">Home</RouterLink>
        <div class="flex flex-grow">
            <input type="search" class="px-2 py-1.5 rounded-md bg-white border border-slate-400 w-full">
        </div>
        <span>
            <p>Logo</p>
        </span>
    </nav>
</template>



<style lang="scss" scoped></style>