<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Crear from '@/Components/Crear.vue';
</script>

<template>
    <AppLayout title="Tareas">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight">
                <button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#staticBackdrop">Crear</button>
                <button type="button" class="btn btn-danger">Eliminar</button>
                <button type="button" class="btn btn-dark">Lista</button>
                <button type="button" class="btn btn-dark">Editar</button>
                <button type="button" class="btn btn-dark">Filtrar</button>
                <button type="button" class="btn btn-dark">Asignar</button>
                <button type="button" class="btn btn-dark">Comentarios</button>
            </h2>

            <div class="modal fade" id="staticBackdrop" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                    <div class="modal-header">
                        <h1 class="modal-title fs-5" id="staticBackdropLabel">Agregar nueva tarea</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="modal-body">
                        <form class="row g-3 needs-validation" novalidate>

                            <div class="mb-3">
                                <label for="exampleInputEmail1" class="form-label">Tarea</label>
                                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                                <div id="emailHelp" class="form-text">Nombre de la tarea</div>
                            </div>

                            <div class="mb-3">
                                <label for="exampleInputEmail1" class="form-label">Descripcion</label>
                                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                                <div id="emailHelp" class="form-text">Describe la tarea</div>
                            </div>


                            <div class="col-md-6">
                                <label for="validationCustom01" class="form-label">Fecha de Inicio</label>
                                <input type="date" class="form-control" id="input-date" name="input-date" min="1900-01-01" max="2030-12-31">
                                <div class="valid-feedback">
                                Looks good!
                                </div>
                            </div>

                        <div class="col-md-6">
                            <label for="validationCustom02" class="form-label">Fecha de Vencimineto</label>
                            <input type="date" class="form-control" id="input-date" name="input-date" min="1900-01-01" max="2030-12-31">
                            <div class="valid-feedback">
                            Looks good!
                            </div>
                        </div>

                        <label for="customRange3" class="form-label">Prioridad</label>
                        <input type="range" class="form-range" min="0" max="5 " step="0.5" id="customRange3">

                        <div class="col-12">
                            <button class="btn btn-primary" type="submit">Guardar</button>
                        </div>

                        </form>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Cerrar</button>
                    </div>
                    </div>
                </div>
            </div>
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
