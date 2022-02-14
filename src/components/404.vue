<template>
  <section class="error-area">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-7">
          <div class="error-thumb text-center">
            <img src="@/assets/images/404.png" alt="" />
          </div>
        </div>
        <div class="col-lg-6">
          <div class="error-content text-center">
            <h3 class="title">Página no encontrada</h3>
            <p>
              Lo sentimos, no se puede encontrar la página que estaba buscando. Intente buscar la mejor coincidencia o navegue por los enlaces a continuación:
            </p>
            <ul>
              <li>
                <a class="main-btn" href @click.prevent="$router.go(-1)">Volver</a>
              </li>
              <li>
                <router-link class="main-btn btn-2" to="/contact">CONTACTO</router-link>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style></style>
