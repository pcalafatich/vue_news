<template>
    <div>
        <drawer @toggleSidebar="toggleSidebar" :sidebar="sidebar" />
        <Header @toggleSidebar="toggleSidebar" />
        <!--====== POST LAYOUT 1 PART START ======-->
        <section class="post-layout-1-area pb-80">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <div class="about-author-content">
                            <nav aria-label="breadcrumb">
                                <ol class="breadcrumb">
                                    <li class="breadcrumb-item"><a href="index.html">Inicio</a></li>
                                    <li class="breadcrumb-item"><a href="#">Noticias del mundo</a></li>
                                    <li class="breadcrumb-item active" aria-current="page">
                                        Salud
                                    </li>
                                </ol>
                            </nav>
                        </div>
                    </div>
                    <div class="col-lg-8">
                        <div class="post-layout-top-content">
                            <div class="
                  post-categories
                  d-flex
                  justify-content-between
                  align-content-center
                ">
                                <div class="categories-item">
                                    <span>SALUD</span>
                                </div>
                                <div class="categories-share">
                                    <ul>
                                        <li><i class="fas fa-comment"></i>45020</li>
                                        <li><i class="fas fa-fire"></i>45020</li>
                                    </ul>
                                </div>
                            </div>
                            <div class="post-content">
                                <h3 class="title">
                                    Exitos en el tratamiento del virus en Japon, la nueva tendencia
                                </h3>
                                <p>
                                    The property, complete with 30-seat screening from room, a
                                    100-seat amphitheater and a swimming pond with sandy shower…
                                </p>
                                <div class="thumb">
                                    <img src="@/assets/images/post-layout.png" alt="" />
                                </div>
                            </div>
                            <div class="post-author">
                                <div class="author-info">
                                    <div class="thumb">
                                        <img src="@/assets/images/author1.png" alt="" />
                                    </div>
                                    <h5 class="title">Esteban de la Vega</h5>
                                    <ul>
                                        <li>March 26, 2020</li>
                                        <li>Updated 1:58 p.m. ET</li>
                                    </ul>
                                </div>
                                <div class="author-social">
                                    <ul>
                                        <li>
                                            <a href="#"><i class="fab fa-facebook-f"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fab fa-twitter"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fab fa-youtube"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fab fa-instagram"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fal fa-heart"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fal fa-bookmark"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fas fa-ellipsis-v"></i></a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                            <div class="post-text mt-30">
                                <p>
                                    Se tomarán ventiladores de ciertos hospitales de Nueva York y se redistribuirán a las partes más afectadas del estado según una orden que firmará el gobernador Andrew Cuomo.
                                </p>
                                <p>
                                    Nueva York experimentó su mayor aumento de muertes en un solo día, con un aumento de 562 a 2935, casi la mitad de todas las muertes estadounidenses relacionadas con virus registradas ayer. La Casa Blanca puede recomendar a las personas que se encuentran en los puntos críticos del virus que se cubran la cara en público para ayudar a detener la propagación.
                                </p>
                                <p>Estados Unidos ahora tiene 245,658 casos de Covid-19.</p>
                                <p>
                                    La escasez de varios cientos de ventiladores en la ciudad de Nueva York, el epicentro del brote en los EE. UU., llevó a Cuomo a decir que ordenará que se retiren las máquinas de varias partes del estado y se las entregue a las áreas más afectadas.
                                    <p>
                                        En medio de una crisis cada vez más profunda, el principal funcionario de salud, el Dr. Anthony Fauci, dijo que cree que todos los estados deberían emitir órdenes de quedarse en casa.
                                    </p>
                                    <p>
                                        “No entiendo por qué eso no está sucediendo”, dijo el Dr. Fauci a CNN el jueves. “Si miras lo que está pasando en este país, simplemente no entiendo por qué no estamos haciendo eso”.
                                    </p>
                                    <p>
                                        “Tienes que poner el pie en el acelerador para reducir ese número”, agregó, refiriéndose a las tasas de infección y mortalidad.
                                    </p>
                                    <ul>
                                        <li><a href="#">¿Deberíamos más de nosotros usar mascarillas?</a></li>
                                        <li><a href="#">Por qué algunos países usan mascarillas y otros no</a>
                                        </li>
                                        <li>
                                            <a href="#">Coronavirus: ¿Son seguras las mascarillas caseras?</a>
                                        </li>
                                    </ul>
                                    <p>
                                       Los comentarios del Dr. Fauci, que dirige el Instituto Nacional de Alergias y Enfermedades Infecciosas, parecen contradecir los del presidente Trump, quien siempre ha descartado la idea de un confinamiento nacional.Los comentarios del Dr. Fauci, que dirige el Instituto Nacional de Alergias y Enfermedades Infecciosas, parecen contradecir los del presidente Trump, quien siempre ha descartado la idea de un confinamiento nacional.
                                    </p>
                                    <p>
                                        “Es terriblemente difícil decir, 'ciérrenlo'. Tenemos que tener un poco de flexibilidad”, dijo Trump el miércoles.
                                    </p>
                            </div>
                            <div class="post-text pt-20">
                                <h5 class="title">¿Cuál es el debate sobre las máscaras?</h5>
                                <p>
                                   Tanto los Centros para el Control de Enfermedades (CDC) de EE. UU. como la Organización Mundial de la Salud (OMS) están reevaluando su orientación sobre las máscaras faciales, ya que los expertos se apresuran a encontrar formas de combatir el virus altamente contagioso.
                                </p>
                                <p>
                                    El covid-19 se transporta en gotitas en el aire de personas que tosen o estornudan, pero existe cierta controversia sobre cuánto deben distanciarse las personas entre sí y si las máscaras son útiles cuando las usa el público.
                                </p>
                                <div class="row pt-10">
                                    <div class="col-lg-6">
                                        <div class="post-thumb">
                                            <img src="@/assets/images/post-thumb-2.png" alt="" />
                                        </div>
                                    </div>
                                    <div class="col-lg-6">
                                        <div class="text">
                                            <p>
                                              La OMS advierte que las máscaras faciales ordinarias solo son efectivas si se combinan con un lavado cuidadoso de las manos y el distanciamiento social, y hasta ahora no las recomienda en general para personas sanas.
                                            </p>
                                            <p>
                                                Sin embargo, cada vez más expertos en salud ahora dicen que hay beneficios. Argumentan que el uso público de máscaras puede ayudar principalmente al evitar que los pacientes asintomáticos (personas que han sido infectadas con Covid-19 pero que no lo saben y que no muestran ningún síntoma) propaguen el virus a otros sin saberlo.
                                            </p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="post-text pt-20">
                                <p>
                                    Las máscaras también pueden ayudar a reducir el riesgo de que las personas contraigan el virus a través de las gotitas del estornudo o la tos de otra persona, y se les puede enseñar a las personas cómo ponerse y quitarse las máscaras correctamente, argumentan.
                                </p>
                                <p>
                                    El jueves, el alcalde de Nueva York, Bill de Blasio, instó a todos los neoyorquinos a cubrirse la cara cuando estén afuera y cerca de otras personas, pero a no usar máscaras quirúrgicas, que escasean.
                                </p>
                                <p>
                                   “Podría ser una bufanda. Podría ser algo que crees tú mismo en casa. Podría ser un pañuelo”, dijo. El gobernador Cuomo intervino el viernes y dijo
                                    <span class="quote-text">“Creo que es justo decir que las máscaras no pueden doler a menos que te den una falsa sensación de seguridad”.</span>
                                </p>
                                <p>
                                   Mientras tanto, los residentes de Laredo, Texas, ahora enfrentarán una multa de $ 1,000 (£ 816) si no se cubren la nariz y la boca mientras están afuera, luego de que los funcionarios de la ciudad emitieran una ordenanza de emergencia para sus aproximadamente 250,000 residentes esta semana.
                                </p>
                            </div>
                            <div class="post-text pt-20">
                                <h5 class="title">¿Qué estados no están encerrados?</h5>
                                <p>
                                    Tanto los Centros para el Control de Enfermedades (CDC) de EE. UU. como la Organización Mundial de la Salud (OMS) están reevaluando su orientación sobre las máscaras faciales, ya que los expertos se apresuran a encontrar formas de combatir el virus altamente contagioso.
                                </p>
                                <p>
                                    El covid-19 se transporta en gotitas en el aire de personas que tosen o estornudan, pero existe cierta controversia sobre cuánto deben distanciarse las personas entre sí y si las máscaras son útiles cuando las usa el público.
                                </p>
                                <div class="thumb pt-20 pb-35">
                                    <img src="@/assets/images/post-thumb-3.jpg" alt="" />
                                    <span>Acabo de tener un bebé, ahora voy al frente.</span>
                                </div>
                                <p>
                                    Las máscaras también pueden ayudar a reducir el riesgo de que las personas contraigan el virus a través de las gotitas del estornudo o la tos de otra persona, y se les puede enseñar a las personas cómo ponerse y quitarse las máscaras correctamente, argumentan.
                                </p>
                                <p>
                                    El jueves, el alcalde de Nueva York, Bill de Blasio, instó a todos los neoyorquinos a cubrirse la cara cuando estén afuera y cerca de otras personas, pero a no usar máscaras quirúrgicas, que escasean.
                                </p>
                                <p>
                                    Mientras tanto, los residentes de Laredo, Texas, ahora enfrentarán una multa de $ 1,000 (£ 816) si no se cubren la nariz y la boca mientras están afuera, luego de que los funcionarios de la ciudad emitieran una ordenanza de emergencia para sus aproximadamente 250,000 residentes esta semana.
                                </p>
                            </div>
                            <div class="post-quote d-block d-md-flex align-items-center">
                                <div class="thumb">
                                    <img src="@/assets/images/post-quote.jpg" alt="" />
                                </div>
                                <div class="post-quote-content">
                                    <img src="@/assets/images/quote-icon.png" alt="" />
                                    <p>
                                        Debo explicarles cómo nació toda esta idea errónea de denunciar el placer y exaltar el dolor y les daré cuenta completa del sistema y expondré las enseñanzas reales del gran explorador de la verdad, el maestro constructor de la felicidad humana. Nadie rechaza, tiene aversión o evita el placer porque es placer.
                                    </p>
                                    <div class="user">
                                        <img src="@/assets/images/author1.png" alt="" />
                                        <h5 class="title">Eduardo Guede</h5>
                                        <span>Enviado en USA</span>
                                    </div>
                                </div>
                            </div>
                            <div class="post-text mt-35">
                                <p>
                                    Al día siguiente volví con mi equipo y dije: Esto es lo que acabo de escuchar, tenemos que prepararnos, dijo. Sabíamos que no pasaría mucho tiempo antes de que tuviéramos que lidiar con eso.
                                </p>
                                <p>
                                   El Sr. Hogan también se ha apoyado en su esposa, Yumi Hogan, una inmigrante coreana, que también estuvo en la convención del gobernador, que incluyó una cena en la casa del embajador de Corea. Como la primera primera dama coreana en la historia de Estados Unidos, la Sra. Hogan se ha convertido en un ícono en Corea del Sur. Agarré a mi esposa y le dije: Mira, hablas coreano. Conoces al presidente. Conoces a la primera dama. Conoces al embajador. Hablemos con ellos en coreano y dígales que necesitamos su ayuda. Las empresas en Corea del Sur dijeron que harían pruebas.
                                </p>
                                <div class="thumb pt-10 pb-35">
                                    <img src="@/assets/images/post-thumb-4.png" alt="" />
                                </div>
                                <p>
                                    En términos globales, EE. UU. tiene la mayor cantidad de casos de Covid-19: más de 245,000. Y el jueves, las autoridades estadounidenses dijeron que más de 1.000 habían muerto en las últimas 24 horas, la cifra diaria más alta hasta ahora en el mundo.
                                </p>
                                <p>
                                    Los hospitales y las morgues de Nueva York están luchando para hacer frente a la pandemia, y el gobernador de Nueva York, Andrew Cuomo, advirtió que Nueva York corre el riesgo de quedarse sin ventiladores para los pacientes en seis días.
                                </p>
                            </div>
                            <div class="post-tags">
                                <ul>
                                    <li>
                                        <a href="#"><i class="fas fa-tag"></i> Etiquetas</a>
                                    </li>
                                    <li><a href="#">Salud</a></li>
                                    <li><a href="#">El Mundo</a></li>
                                    <li><a href="#">Coronavirus</a></li>
                                </ul>
                            </div>
                            <div class="post-reader-text pt-50">
                                <div class="row">
                                    <div class="col-md-6">
                                        <div class="post-reader-prev">
                                            <span>ANTERIOR</span>
                                            <h4 class="title">
                                                <a href="#">Kushner se pone en medio de la caótica respuesta al coronavirus de la Casa Blanca.</a>
                                            </h4>
                                        </div>
                                    </div>
                                    <div class="col-md-6">
                                        <div class="post-reader-prev">
                                            <span>SIGUIENTE</span>
                                            <h4 class="title">
                                                <a href="#">CIA Caza de totales auténticos de virus en China, descartando los recuentos del gobierno</a>
                                            </h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <style-one :datas="Posts" />
                    </div>
                </div>
            </div>
        </section>
        <!--====== POST LAYOUT 1 PART ENDS ======-->
        <!--====== LATEST NEWS PART START ======-->
        <our-latest-news :Posts="Posts" />
        <!--====== LATEST NEWS PART ENDS ======-->
        <!--====== POST FORM PART START ======-->
        <div class="post-form-area">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-10">
                        <div class="section-title">
                            <h3 class="title">Comentarios</h3>
                        </div>
                        <div class="post-form-box">
                            <form action="#">
                                <div class="row">
                                    <div class="col-lg-6">
                                        <div class="input-box">
                                            <input type="text" placeholder="Nombre y apellido" />
                                        </div>
                                    </div>
                                    <div class="col-lg-6">
                                        <div class="input-box">
                                            <input type="text" placeholder="Correo electrónico" />
                                        </div>
                                    </div>
                                    <div class="col-lg-12">
                                        <div class="input-box">
                                            <textarea name="#" id="#" cols="30" rows="10" placeholder="Por favor deje aquí su comentario"></textarea>
                                            <button class="main-btn" type="button">
                                                ENVIAR
                                            </button>
                                        </div>
                                    </div>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!--====== POST FORM PART ENDS ======-->
        <!--====== POST COMMENTS PART START ======-->
        <section class="post-comments-area pb-100">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-10">
                        <div class="section-title">
                            <h3 class="title">Comentarios</h3>
                        </div>
                        <div class="post-comments-list">
                            <div class="post-comments-item">
                                <div class="thumb">
                                    <img src="@/assets/images/comments-1.png" alt="comentarios" />
                                </div>
                                <div class="post">
                                    <a href="#">Responder</a>
                                    <h5 class="title">Esteban de la Vega</h5>
                                    <p>
                                        Suspendisse potenti. Aenean finibus vitae velit nec dapibus. Donec eu aliquam urna, vitae tincidunt tellus. Vivamus egestas massa vitae porttitor ullamcorper. Aliquam vestibulum massa sit amet massa mollis porttitor. Vestibulum id lorem pulvinar, consectetur quam quis, convallis velit. Nullam eget aliquam nunc.
                                    </p>
                                </div>
                            </div>
                            <div class="post-comments-item">
                                <div class="thumb">
                                    <img src="@/assets/images/comments-2.png" alt="comentarios" />
                                </div>
                                <div class="post">
                                    <a href="#">Responder</a>
                                    <h5 class="title">Esteban de la Vega</h5>
                                    <p>
                                        Suspendisse potenti. Aenean finibus vitae velit nec dapibus. Donec eu aliquam urna, vitae tincidunt tellus. Vivamus egestas massa vitae porttitor ullamcorper. Aliquam vestibulum massa sit amet massa mollis porttitor. Vestibulum id lorem pulvinar, consectetur quam quis, convallis velit. Nullam eget aliquam nunc.
                                    </p>
                                </div>
                            </div>
                            <div class="post-comments-item ml-30">
                                <div class="thumb">
                                    <img src="@/assets/images/comments-3.png" alt="comentarios" />
                                </div>
                                <div class="post">
                                    <a href="#">Responder</a>
                                    <h5 class="title">Esteban de la Vega</h5>
                                    <p>
                                        Suspendisse potenti. Aenean finibus vitae velit nec dapibus. Donec eu aliquam urna, vitae tincidunt tellus. Vivamus egestas massa vitae porttitor ullamcorper. Aliquam vestibulum massa sit amet massa mollis porttitor. Vestibulum id lorem pulvinar, consectetur quam quis, convallis velit. Nullam eget aliquam nunc.
                                    </p>
                                </div>
                            </div>
                            <div class="post-comments-item">
                                <div class="thumb">
                                    <img src="@/assets/images/comments-4.png" alt="comentarios" />
                                </div>
                                <div class="post">
                                    <a href="#">Responder</a>
                                    <h5 class="title">Esteban de la Vega</h5>
                                    <p>
                                        Suspendisse potenti. Aenean finibus vitae velit nec dapibus. Donec eu aliquam urna, vitae tincidunt tellus. Vivamus egestas massa vitae porttitor ullamcorper. Aliquam vestibulum massa sit amet massa mollis porttitor. Vestibulum id lorem pulvinar, consectetur quam quis, convallis velit. Nullam eget aliquam nunc.
                                    </p>
                                </div>
                            </div>
                        </div>
                        <div class="post-load-btn">
                            <a class="main-btn" href="#">CARGAR MAS</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--====== POST COMMENTS PART ENDS ======-->
        <!--====== ADD PART ENDS ======-->
        <div class="add-area text-center">
            <a href="#">
                <img src="@/assets/images/ads/one_ad.png" alt="" />
            </a>
        </div>
        <!--====== ADD PART ENDS ======-->
        <footer-one />
        <div class="go-top-area">
            <div class="go-top-wrap">
                <div class="go-top-btn-wrap">
                    <a href="#" class="go-top go-top-btn d-block">
                        <i class="fa fa-angle-double-up"></i>
                        <i class="fa fa-angle-double-up"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import Header from "../../Utility/Header/index";
import StyleOne from "../../Utility/Sidebar/StyleOne.vue";
import Posts from "../../Data/NewsRowCard";
import FooterOne from "../../Utility/Footer/FooterOne.vue";
import OurLatestNews from "../../Utility/Common/OurLatestNews.vue";
import Drawer from "../../Mobile/Drawer.vue";
export default {
    components: { Header, StyleOne, FooterOne, OurLatestNews, Drawer },
    data: () => ({
        Posts: Posts.data,
        sidebar: false,
    }),
    created() {
        document.addEventListener("scroll", this.topToBottom);
    },
    methods: {
        toggleSidebar() {
            this.sidebar = !this.sidebar;
        },
        topToBottom() {
            const result = document.querySelector(".go-top");
            if (
                document.body.scrollTop > window.innerHeight ||
                document.documentElement.scrollTop > window.innerHeight
            ) {
                result.classList.add("active");
            } else {
                result.classList.remove("active");
            }
        },
    },
};
</script>
<style></style>