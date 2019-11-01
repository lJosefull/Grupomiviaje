<template>

    <div id="contenedor">

        <div id="contenedor-1">

          <div id="bloque">
                    <li>LINEA DE ATENCIÓN (5) 3557755</li>
                    <li>WHATSAPP: +57(318)546-4537</li>
                    <li>SIGUENOS EN REDES: </li>
                    <li>ESPAÑOL/ENGLISH</li>
                </div>


                 <div id="header">
                    <div id="logo-1">
                        <img src="../img/logo.png" alt="">
                    </div>
                    <div id="nav">
                        <li><a href="#" >INICIO</a></li>
                        <li><a href="#" >NOSOTROS</a></li>
                        <li><a href="#" >RESERVA TIQUETES</a></li>
                        <li><a href="#" >DESTINOS</a></li>
                        <li><a href="#" >DESTINOS</a></li>
                        <li><a href="#" >SERVICIOS</a></li>
                        <li><a href="#" ><b>CONTÁCTANOS</b></a></li>
                        <li><a href="#" id="escribenos">ESCRIBENOS</a></li>
                        <img id="icono-whatsapp" src="../img/icono-whatsapp.png" alt="">
                    </div>
                 </div>

        </div>
    </div>

</template>

<style lang="scss">

@import url('https://fonts.googleapis.com/css?family=Annie+Use+Your+Telescope&display=swap');

$color-base:#FF8C3D;
$color-base-2:white;

   *{
       padding:0px;
       margin:0px;
       box-sizing:border-box;
       list-style-type:none;
       font-family:  cursive;
       border:none;
   }


    #contenedor{
        width:100%;
        height:100%;
    }

    #contenedor-1{
        width:100%;
        height:100vh;

    a{
       text-decoration: none;
     }

   #bloque{
       display: flex;
       flex-direction: row;
       justify-content: space-around;
       background-color:$color-base;
       color:white;
       padding:1em 1em;

       li{
           font-size:.9em;
       }

       img{
           width:25px;
           height:25px;
           margin:0px 4px 3px 4px;
       }
   }


   #header{
       display: flex;
       width:100%;
       height:20vh;
       justify-content: flex-end;
       background-color:$color-base-2;
       align-items: center;

       #logo-1 img{
           width:180px;
           transform: translate(-50%,0%);
       }

       #nav{
            display: flex;
            margin-right: 7%;

           li{
               padding:.5em 1em;
               margin:0px 10px;
               font-size: .8em;
           }

           #escribenos{
               padding:1em 2.5em;
               background-color:$color-base;
               border-radius: 15px;
               color:white;
           }

           #icono-whatsapp{
               width:50px;
               transform: translate(-90%,-25%);
           }
       }
   }
    }

//Dispositivos extra pequeños
@media only screen and(max-width:600px){

}

//Dispositivos pequeños
@media only screen and(min-width:600px){

}

//Dispositivos medianos
@media only screen and(max-width:768px){

}

//Dispositivos grandes
@media only screen and(max-width:992px){

}

//Dispositivos extra grandes
@media only screen and(max-width:1200px){

}


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
