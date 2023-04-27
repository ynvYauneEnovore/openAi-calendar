<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
</script>

<template>
    <AppLayout title="Dashboard">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight">
                Noticias & Ofertas:
            </h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white dark:bg-gray-800 overflow-hidden shadow-xl sm:rounded-lg">
                    <Welcome />
                </div>
            </div>
        </div>

        <template #footer>
            <div class="text-white text-center" style="padding-top: 20px;">
                Yovan Ram&oacute;n Yaune Enovore &copy; 2023
                <hr>
                <a href="#" class="link-info">Success link</a><br>
                <a href="#" class="link-info">Success link</a>
            </div>
        </template>
    </AppLayout>
</template>
