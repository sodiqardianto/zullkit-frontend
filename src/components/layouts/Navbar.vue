<script setup>
import { RouterLink } from 'vue-router'
import Logo from '@/components/layouts/Logo.vue'
import UserInfo from '@/components/layouts/UserInfo.vue'
import NavigationLink from '@/components/layouts/NavigationLink.vue'
import AuthButton from '@/components/layouts/AuthButton.vue'
</script>

<template>
    <nav class="bg-white border-gray-200 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-800">
        <div class="container flex flex-wrap items-center justify-between mx-auto my-2">
            <Logo />
            <AuthButton />
            <!-- <UserInfo /> -->
            <NavigationLink />
        </div>
    </nav>
</template>