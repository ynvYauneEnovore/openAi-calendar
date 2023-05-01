<template #main>
<div class="container w-40">
<div id="carouselExampleCaptions" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4" aria-label="Slide 5"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="5" aria-label="Slide 6"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="6" aria-label="Slide 7"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/img/card-4.png" class="d-block w-100 h-82" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h3>Crear</h3>
        <p>Permite a los usuarios agregar nuevas tareas con sus respectivos detalles, como descripción, fecha de inicio, fecha de vencimiento, prioridad.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/img/card-5.png" class="d-block w-100 h-82" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h3 class="text-dark">Eliminar</h3>
        <p class="text-dark">Permite a los usuarios eliminar tareas que ya no sean necesarias o que hayan sido completadas.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/img/card-6.png" class="d-block w-100 h-82" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h3>Listar</h3>
        <p>Muestra todas las tareas disponibles en el sistema en una tabla o lista, ordenadas por fecha de vencimiento o por prioridad, según corresponda. Permite a los usuarios ver el estado de cada tarea y si ha sido completada o no.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/img/card-7.png" class="d-block w-100 h-82" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h3>Editar</h3>
        <p>Permite a los usuarios actualizar los detalles de una tarea existente, como la descripción, la fecha de inicio, la fecha de vencimiento, la prioridad.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/img/card-8.png" class="d-block w-100 h-82" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h3>Filtrar</h3>
        <p>Ofrece opciones de filtrado para que los usuarios puedan ver solo las tareas que les interesen, por ejemplo, aquellas que estén asignadas a ellos o aquellas que tengan una fecha de vencimiento próxima.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/img/card-9.png" class="d-block w-100 h-82" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h3>Asignar</h3>
        <p>Permite a los usuarios asignar tareas a otros usuarios, si el sistema cuenta con roles y permisos que lo permitan.</p>
      </div>
      </div>
      <div class="carousel-item">
      <img src="/img/card-7.png" class="d-block w-100 h-82" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h3>Comentarios</h3>
        <p>Ofrece la posibilidad de que los usuarios agreguen comentarios o notas a las tareas, para mantener un registro de su progreso o cualquier otra información relevante.</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>
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
