<template>
  <div class="about-author-area">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="about-author-content">
            <nav aria-label="breadcrumb">
              <ol class="breadcrumb">
                <li class="breadcrumb-item"><a href="index.html">Inicio</a></li>
                <li class="breadcrumb-item"><a href="#">Autor</a></li>
                <li class="breadcrumb-item active" aria-current="page">
                  The wave of Pride
                </li>
              </ol>
            </nav>
            <div class="author-content">
              <div class="thumb">
                <img
                  src="@/assets/images/author1.png"
                  alt=""
                  style="width: 80px; height: 80px"
                />
              </div>
              <h3 class="title">Eduardo Guede</h3>
              <ul>
                <li>Redactor</li>
                <li>
                  <span>Desde: <span>15 Marzo de 2020</span></span>
                </li>
              </ul>
              <div class="text">
                <p>
                  Eduardo Guede es un periodista de investigacion para RaitNau Digital, domiciliado en Huelva. Comenzó su carrera trabajando en El Heraldo en el año 1999 cubriendo la sección Política y Economica del periódico.
                </p>
                <p>
                  Ha ganado numerosas premios por reportajes explicativos, reportajes de investigación y como parte del equipo de reportajes extranjeros. Anteriormente trabajó en El País y El Heraldo.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.author-content .thumb {
  position: absolute;
  left: 0;
  top: 0;
  border-radius: 50%;
  overflow: hidden;
  height: 115px;
  width: 115px;
  text-align: center;
  line-height: 112px;
  border: 2px solid #e4e5e6;
}
</style>
