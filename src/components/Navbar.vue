<template>
    <div class="main">
      <nav class="navbar navbar-expand-lg bg-body-tertiary fixed-top bg-info" style="background-color: purple;">
        <div class="container-fluid">
          <a class="navbar-brand" href="/">Portafolio</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="Introduccion">Introduccion</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" href="SdC">Sumario de contenidos</a>
              </li>
              <li><a class="nav-link active" href="Tareas">Tareas ex-aula</a></li>
              <li><a class="nav-link active" href="Investigaciones">Investigaciones</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style>
  
  </style>