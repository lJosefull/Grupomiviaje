<template>

    <div id="contenedor">

        <div id="contenedor-1">

            <div id="banner-1">
                <div id="banner-consulta-1">
                    <h2>CONSULTA TU VIAJE AQUÍ</h2>
                    <div id="inputs-1">
                        <input id="input-origen" type="text" placeholder="ORIGEN">
                        <input id="input-destino" type="text" placeholder="DESTINO">
                        <input type="datetime-local" placeholder="FECHA SALiDA">
                        <input type="datetime-local" placeholder="REGRESO">
                    </div>
                    <button type="submit">BUSCAR OPCIONES</button>
                </div>
            </div>

        </div>

        <div id="contenedor-2">

            <div id="slogan-1">
                <img src="../img/logo-avion-1.png" alt="">
                <h2>Paquetes <br> de viaje</h2>
            </div>

            <div id="destinos-2">

                <figure id="figure-1">
                    <div class="paquetes">
                        <span>Santa Marta Tour</span><br>
                        <span>Santa Marta</span><br>
                        <span class="precio-nulo">$360.000</span><br>
                        <span>$320.000</span><br>
                    </div>
                </figure>

                <figure id="figure-2">
                     <div class="paquetes">
                        <span>Barranquilla Tour</span><br>
                        <span>Barranquilla</span><br>
                        <span class="precio-nulo">$260.000</span><br>
                        <span>$220.000</span><br>
                     </div>
                </figure>

                 <figure id="figure-3">
                    <div class="paquetes">
                        <span>Cartagena Tour</span><br>
                        <span>Cartagena</span><br>
                        <span class="precio-nulo">$260.000</span><br>
                        <span >$220.000</span><br>
                        </div>
                </figure>

                <figure id="figure-4">
                    <div class="paquetes">
                        <span>Valledupar Tour</span><br>
                        <span>Valledupar</span><br>
                        <span class="precio-nulo">$120.000</span><br>
                        <span>$80.000</span><br>
                    </div>
                </figure>

            </div>

        </div>

        <div id="contenedor-3">
            <div id="avion-1">
                <img src="../img/avion-1.png" alt="logo-avion">
            </div>
            <div id="carrusel">
                <button class="flecha" type="submit"><img src="../img/flecha-izquierda.png" alt="flecha-izquierda"></button>
                <div class="carrusel-1">
                    <img src="../img/santa_marta-2.jpg" alt="">
                    <div>
                        <h3></h3>
                        <span></span>
                    </div>
                </div>
                <div class="carrusel-1">
                    <img src="../img/valledupar-2.jpg" alt="">
                    <div>
                        <h3></h3>
                        <span></span>
                    </div>
                </div>
                <div class="carrusel-1">
                    <img src="../img/cartagena-2.jpg" alt="">
                    <div>
                        <h3></h3>
                        <span></span>
                    </div>
                </div>
                <button class="flecha" type="submit"><img src="../img/flecha-derecha.png" alt="flecha-derecha"></button>
            </div>
        </div>


        <div id="contenedor-4">
            <div id="noticias">
                <div id="ingresar-datos-slogan">
                    <div id="ingresar-datos">
                        <div id="nombre-email">
                            <input id="nombre" type="text" placeholder="Nombre"><br>
                            <input id="email" type="email" placeholder="Correo Electronico">
                        </div>
                        <div id="flecha-boton">
                            <button type="submit"><img src="../img/flecha-boton-2.png" alt=""></button>
                        </div>
                    </div>
                    <div id="slogan-2">
                        <span>Dejanos tus datos y te enviaremos a tu correo <br>
                        electronico promociones y nuevos destinos o rutas.</span>
                    </div>

                </div>
                <div id="slogan-3">
                    <span>Recibe las últimas noticias <br>y promociones exclusivas</span>
                </div>


            </div>
        </div>


    </div>

</template>
<style lang="scss">
  @import "../../sass/style.scss";
</style>

<script>
    export default {
        mounted(){
            console.log('Component mounted.')
        },
        data:{

        },
        method:{

        }
}


</script>
