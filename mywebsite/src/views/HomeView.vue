<template>
  <div>
    <NavbarComponentVue
      nav1="nav-link active"
      nav2="nav-link"
      nav3="nav-link"
      nav4="nav-link"
    />

    <!-- Container -->
    <div class="container mb-3 mb-lg-4">
      <div class="row p-0 justify-content-center">
        <!-- Presentación -->
        <div class="col-lg-8 col-10">
            <h3 style="color:gray;">Presentación</h3>
        </div>

        <div class="col-lg-8 col-10 border shadow rounded row p-3 justify-content-center bg-star">
          <img
            src="@/assets/yo.jpeg"
            alt="Camilo Paternina"
            class="col-12 col-lg-4 rounded-circle shadow p-0"
            style="height: 260px; width: 190px"
          />
          <div class="col-12 col-lg-8 justify-content-center mt-3 mt-lg-0">
            <h2>Camilo Paternina</h2>
            <h5 style="color: #0009;">Estudiante de ingeniería de Sistemas</h5>
            <h6 style="color: #0009;">Universidad de Córdoba</h6>
            <hr>
            <p>Me considero un amante de la tecnología, me interesa explorar nuevas herramientas y nunca parar de aprender. <br>Estoy cursando noveno semestre en la Universidad de Córdoba en Colombia, espero que podamos trabajar juntos, estoy seguro que podemos alcanzar cosas muy grandes :).</p>
          </div>
        </div>

        <!-- Mis Proyectos -->
        <div class="col-lg-8 col-10 mt-4">
            <h3 style="color:gray;" id="Mis Proyectos">Mis Proyectos</h3>
        </div>
        <div class="col-10 col-lg-8 border shadow rounded row p-3 justify-content-around bg-star">
          <div class="card col-12 col-lg-5 bg-star">
            <div class="card-body">
              <h5 class="card-title">Lalila</h5>
              <hr>
              <p class="card-text">Lalila fue un proyecto ganador de la Hackaton3.0 de MINTIC en 2021, el proyecto aún sigue en desarrollo.</p>
            </div>
          </div>

          <div class="card col-12 col-lg-5 mt-3 mt-lg-0 bg-star">
            <div class="card-body">
              <h5 class="card-title">YoutubeDownload</h5>
              <hr>
              <p class="card-text">Software desarrollado en Java donde se implementa una interfaz gráfica de usuarios del script Youtube-dl.</p>
            </div>
          </div>
        </div>

        <!-- Mis Habilidades -->
        <div class="col-lg-8 col-10 mt-4">
            <h3 style="color:gray;" id="Mis Habilidades">Mis Habilidades</h3>
        </div>
        <div class=" bg-star col-10 col-lg-8 border shadow rounded row p-3 justify-content-center">
          
          <div class="col-12 col-lg-3 row  justify-content-center text-center">
            <img src="@/assets/Habilidades/Java.png" alt="Java" class="rounded-circle col-12" style="height: 120px;width:120px ;">
            <hr class="mt-2">
            <p>3 semestres aprobados de POO usando Java</p>
          </div>

          <div class="col-12 col-lg-3 row justify-content-center text-center">
            <img src="@/assets/Habilidades/Js.png" alt="Js" class=" rounded-circle col-12" style="height: 120px;width:140px ;">
            <hr class="mt-2">
            <p>1 semestre aprobado en Desarrollo Web</p>
          </div>

          <div class="col-12 col-lg-3 row  justify-content-center text-center">
            <img src="@/assets/Habilidades/Php.png" alt="Php" class=" rounded-circle col-12" style="height: 120px;width:140px ;">
            <hr class="mt-2">
            <p>1 semestre aprobado en Desarrollo Web</p>
          </div>

          <div class="col-12 col-lg-3 row  justify-content-center text-center">
            <img src="@/assets/Habilidades/Laravel.png" alt="Laravel" class=" rounded-circle col-12" style="height: 120px;width:140px ;">
            <hr class="mt-2">
            <p>1 semestre aprobado en Desarrollo Web</p>
          </div>

          <div class="col-12 col-lg-3 row  justify-content-center text-center">
            <img src="@/assets/Habilidades/MySQL.png" alt="MySQL" class=" rounded-circle col-12" style="height: 120px;width:140px ;">
            <hr class="mt-2">
            <p>2 semestres aprobados en BD relacionales</p>
          </div>

          <div class="col-12 col-lg-3 row  justify-content-center text-center">
            <img src="@/assets/Habilidades/Vue.png" alt="Vue" class=" rounded-circle col-12" style="height: 120px;width:140px ;">
            <hr class="mt-2">
            <p>1 semestre aprobado en Desarrollo Web</p>
          </div>
        </div>

        <!-- Mis Viajes -->
        <div class="col-lg-8 col-10 mt-4">
            <h3 style="color:gray;" id="Lugares">Lugares</h3>
        </div>
        <div class=" bg-star col-10 col-lg-8 border shadow rounded row p-3 justify-content-center">
          <div class="col-12 col-lg-4 row  justify-content-center text-center">
            <img src="@/assets/Lugares/Santa_Marta.jpeg" alt="Santa Marta" class="col-12 rounded-circle" style="height: 200px;width:200px ;">
            <p>Parque Tayrona (Santa Marta)</p>
          </div>

          <div class="col-12 col-lg-4 row  justify-content-center text-center">
            <img src="@/assets/Lugares/San_Antero.jpeg" alt="San Antero" class="col-12 rounded-circle" style="height: 200px;width:200px ;">
            <p>Playas de San Antero (Córdoba)</p>
          </div>

          <div class="col-12 col-lg-4 row  justify-content-center text-center">
            <img src="@/assets/Lugares/Buritaca.jpeg" alt="Buritaca" class="col-12 rounded-circle" style="height: 200px;width:200px ;">
            <p>Buritaca (Santa Marta)</p>
          </div>

          <div class="col-12 col-lg-4 row  justify-content-center text-center">
            <img src="@/assets/Lugares/Montería.jpeg" alt="Montería" class="col-12 rounded-circle" style="height: 200px;width:200px ;">
            <p>Montería (Córdoba)</p>
          </div>
        </div>
      </div>
    </div>

    <FooterComponentVue></FooterComponentVue>
  </div>
</template>

<script>
import NavbarComponentVue from "@/components/NavbarComponent.vue";
import FooterComponentVue from "@/components/FooterComponent.vue";
export default {
  components: {
    NavbarComponentVue,
    FooterComponentVue,
},
  created() {
    document.title = "Camilo Paternina - Inicio";
  },
};
</script>

<style scoped>
h3{
  text-shadow: 1px 1px 7px hsla(0, 1%, 20%, 0.4);
}
</style>

<style>
.bg-star{
  background-color:rgba(220, 214, 214, 0.8);
}
</style>