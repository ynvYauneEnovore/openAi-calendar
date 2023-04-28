<template #main>

<div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100">
      <img src="/img/card.png" class="card-img-top" alt="/img/card.png">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="/img/card.png" class="card-img-top" alt="/img/card.png">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a short card.</p>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="/img/card.png" class="card-img-top" alt="/img/card.png">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content.</p>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="/img/card.png" class="card-img-top" alt="/img/card.png">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
</div>

    <div class="row">
    <div class="col-sm-6">
        <div class="card bg-dark text-white">
        <div class="card-body">
            <h5 class="card-title">Creación de nuevas tareas</h5>
            <p class="card-text">Permite a los usuarios agregar nuevas tareas con sus respectivos detalles, como descripción, fecha de inicio, fecha de vencimiento, prioridad.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
        </div>
    </div>
    <div class="col-sm-6">
        <div class="card bg-dark text-white">
        <div class="card-body">
            <h5 class="card-title">Creación de nuevas tareas</h5>
            <p class="card-text">Permite a los usuarios agregar nuevas tareas con sus respectivos detalles, como descripción, fecha de inicio, fecha de vencimiento, prioridad.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
        </div>
    </div>
    <div class="col-sm-6">
        <div class="card bg-dark text-white">
        <div class="card-body">
            <h5 class="card-title">Listado de tareas</h5>
            <p class="card-text">Muestra todas las tareas disponibles en el sistema en una tabla o lista, ordenadas por fecha de vencimiento o por prioridad, según corresponda. Permite a los usuarios ver el estado de cada tarea y si ha sido completada o no.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
        </div>
    </div>
    <div class="col-sm-6">
        <div class="card bg-dark text-white">
        <div class="card-body">
            <h5 class="card-title">Edición de tareas</h5>
            <p class="card-text">Permite a los usuarios actualizar los detalles de una tarea existente, como la descripción, la fecha de inicio, la fecha de vencimiento, la prioridad.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
        </div>
    </div>
    <div class="col-sm-6">
        <div class="card bg-dark text-white">
        <div class="card-body">
            <h5 class="card-title">Eliminación de tareas</h5>
            <p class="card-text">Permite a los usuarios eliminar tareas que ya no sean necesarias o que hayan sido completadas.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
        </div>
    </div>
    </div>


        <h5>
            Filtrado de tareas
        </h5>
        <p>
            Ofrece opciones de filtrado para que los usuarios puedan ver solo las tareas que les interesen, por ejemplo, aquellas que estén asignadas a ellos o aquellas que tengan una fecha de vencimiento próxima.
        </p>
        <h5>
            Asignación de tareas
        </h5>
        <p>
            Permite a los usuarios asignar tareas a otros usuarios, si el sistema cuenta con roles y permisos que lo permitan.
        </p>
        <h5>
            Comentarios y notas
        </h5>
        <p>
            Ofrece la posibilidad de que los usuarios agreguen comentarios o notas a las tareas, para mantener un registro de su progreso o cualquier otra información relevante.</p>
  </template>

  <script>
    export default {
      props: {

      }
    }
  </script>
<style>
.dark-bg {
  background-color: #333; /* Cambia este valor al color de fondo deseado */
}

</style>
