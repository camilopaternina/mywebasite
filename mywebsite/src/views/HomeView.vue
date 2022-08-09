<template>
  <div>
    <NavbarComponentVue
      nav1="nav-link active"
      nav2="nav-link"
      nav3="nav-link"
      nav4="nav-link"
    />

    <!-- Container -->
    <div class="container">
      <div class="row p-0 justify-content-center">
        <!-- Presentación -->
        <div class="col-lg-8 col-10">
            <h3 style="color:gray;">Presentación</h3>
        </div>
        <div class="col-lg-8 col-10 border shadow rounded-start row p-3 justify-content-center">
          <img
            src="@/assets/yo.jpeg"
            alt="Camilo Paternina"
            class="col-12 col-lg-4 rounded-circle shadow p-0"
            style="height: 260px; width: 200px"
          />
          <div class="col-12 col-lg-8 justify-content-center mt-3 mt-lg-0">
            <h2>Camilo Paternina</h2>
            <h5 style="color:gray;">Estudiante de ingenieria de Sistemas</h5>
            <h6 style="color:gray;">Universidad de Córdoba</h6>
            <hr>
            <p>Me considero un amante de la tecnología, me interesa explorar nuevas herramientas y nunca parar de aprender. <br>Estoy cursando noveno semestre en la Universidad de Córdoba en Colombia, espero que podamos trabajar juntos, estoy seguro que podemos alcanzar cosas muy grandes :).</p>
          </div>
        </div>

        <!-- Mis Proyectos -->
        <div class="col-lg-8 col-10 mt-4">
            <h3 style="color:gray;" id="Mis Proyectos">Mis Proyectos</h3>
        </div>
        <div class="col-10 col-lg-8 border shadow rounded-start row p-3 justify-content-around">
          <div class="card col-12 col-lg-5">
            <div class="card-body">
              <h5 class="card-title">Lalila</h5>
              <hr>
              <p class="card-text">Lalila fue un proyecto ganador de la Hackaton3.0 de MINTIC en 2021, el proyecto aún sigue en desarrollo.</p>
            </div>
          </div>

          <div class="card col-12 col-lg-5 mt-3 mt-lg-0">
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
        <div class="col-10 col-lg-8 border shadow rounded-start row p-3 justify-content-center">

        </div>

        <!-- Mis Viajes -->
        <div class="col-lg-8 col-10 mt-4">
            <h3 style="color:gray;" id="Mis Viajes">Mis Viajes</h3>
        </div>
        <div class="col-10 col-lg-8 border shadow rounded-start row p-3 justify-content-center">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavbarComponentVue from "@/components/NavbarComponent.vue";
export default {
  components: {
    NavbarComponentVue,
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