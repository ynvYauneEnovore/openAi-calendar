<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Crear from '@/Components/Crear.vue';
</script>

<template>
    <AppLayout title="Tareas">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight">
                <button type="button" class="btn btn-success">Crear</button>
                <button type="button" class="btn btn-danger">Eliminar</button>
                <button type="button" class="btn btn-dark">Lista</button>
                <button type="button" class="btn btn-dark">Editar</button>
                <button type="button" class="btn btn-dark">Filtrar</button>
                <button type="button" class="btn btn-dark">Asignar</button>
                <button type="button" class="btn btn-dark">Comentarios</button>
            </h2>
        </template>

        <template #main>
            <Crear />
        </template>

        <template #footer>
            <div class="text-white text-center" style="padding-top: 20px;">
                Yovan Ram&oacute;n Yaune Enovore &copy; 2023
                <hr>
                <a href="#" class="link-info">Success link</a><br>
            </div>
        </template>
    </AppLayout>
</template>
