<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light shadow p-3 mb-3 mb-lg-4 rounded">
      <div class="container">
        <a class="navbar-brand" href="#" style="font-size: 25px; margin-left: 3px;">Camilo Paternina</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mb-2 mb-lg-0" style="margin-right: auto; ">
            <li class="nav-item">
              <a :class="nav1" aria-current="page" href="#">Inicio</a>
            </li>
            <li class="nav-item">
              <a :class="nav2" href="#Mis Proyectos">Proyectos</a>
            </li>
            <li class="nav-item">
              <a :class="nav3" aria-current="page" href="#">Habilidades</a>
            </li>
            <li class="nav-item">
              <a :class="nav4" href="#">Mis viajes</a>
            </li>
            <li class="nav-item">
              <a :class="nav4" href="https://github.com/camilopaternina" target="_blank">Mi GitHub</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default{
    props:{
        nav1: String,
        nav2: String,
        nav3: String,
        nav4:String
    }
}
</script>