<template>
    <div>
      <h1></h1>
      <p>
        Creación de nuevas tareas: Permite a los usuarios agregar nuevas tareas con sus respectivos detalles, como descripción, fecha de inicio, fecha de vencimiento, prioridad, etc.

Listado de tareas: Muestra todas las tareas disponibles en el sistema en una tabla o lista, ordenadas por fecha de vencimiento o por prioridad, según corresponda. Permite a los usuarios ver el estado de cada tarea y si ha sido completada o no.

Edición de tareas: Permite a los usuarios actualizar los detalles de una tarea existente, como la descripción, la fecha de inicio, la fecha de vencimiento, la prioridad, etc.

Eliminación de tareas: Permite a los usuarios eliminar tareas que ya no sean necesarias o que hayan sido completadas.

Filtrado de tareas: Ofrece opciones de filtrado para que los usuarios puedan ver solo las tareas que les interesen, por ejemplo, aquellas que estén asignadas a ellos o aquellas que tengan una fecha de vencimiento próxima.

Asignación de tareas: Permite a los usuarios asignar tareas a otros usuarios, si el sistema cuenta con roles y permisos que lo permitan.

Comentarios y notas: Ofrece la posibilidad de que los usuarios agreguen comentarios o notas a las tareas, para mantener un registro de su progreso o cualquier otra información relevante.
      </p>
      Para una mejor destresa del algoritmo de compresion debemos integrar el manejo de datos a escala definica por medio
      de distribucion pero dentro del sistema operativo, mejorando la escalabilidad de los servicios.
      <button class="btn-light" @click="createTask">Crear nueva tarea</button>
    </div>
  </template>

  <script>
  export default {
    methods: {
      createTask() {
        // Lógica para crear una nueva tarea
      },
    },
  };
  </script>
