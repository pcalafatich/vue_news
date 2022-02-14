<template>
    <section class="contact-area pb-90">
        <div class="container">
            <div class="row">
                <div class="col-lg-8">
                    <div class="contact-box">
                        <form action="#">
                            <h3 class="title">
                                ¿Desea colaborar con nosotros? <br />
                                Complete el formulario.
                            </h3>
                            <div class="row">
                                <div class="col-md-6">
                                    <div class="input-box">
                                        <input type="text" placeholder="Apellido y Nombre" />
                                    </div>
                                </div>
                                <div class="col-md-6">
                                    <div class="input-box">
                                        <input type="text" placeholder="Asunto" />
                                    </div>
                                </div>
                                <div class="col-md-6">
                                    <div class="input-box">
                                        <input type="email" placeholder="Correo electrónico" />
                                    </div>
                                </div>
                                <div class="col-md-6">
                                    <div class="input-box">
                                        <input type="email" placeholder="Teléfono" />
                                    </div>
                                </div>
                                <div class="col-lg-12">
                                    <div class="input-box">
                                        <textarea name="#" id="#" cols="30" rows="10" placeholder="Escriba su mensaje aquí…"></textarea>
                                        <button class="main-btn">ENVIAR MENSAJE</button>
                                    </div>
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="contact-sidebar">
                        <FromCount />
                        <signup-style-one />
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import FromCount from "../Utility/FollowCount/index";
import SignupStyleOne from "../Utility/Signup/SignupStyleOne.vue";
export default {
    components: { FromCount, SignupStyleOne },
};
</script>
<style></style>