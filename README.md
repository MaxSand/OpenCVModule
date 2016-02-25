# OpenCVModule

Modulo compilado para la utilizacion de <b>Open CV 3.0</b> para desarrollo en Android dentro del IDE Android Studio.
Module compiled for the use of <b>Open CV 3.0</b> for Android within the Android Studio IDE development.

<h3>Pasos para su uso</h3>
<ol>
  <li> <h4>Descargar y extraer</h4> 
      <p>Descargar el repositorio en tu equipo y extrar desde el directorio del modulo la carpeta jniLibs.</p>
  <li> <h4>Importar Modulo</h4>
      <p>Abre tu proyecto Android studio o Inicia uno nuevo, una ves dentro importa el modulo ya descargado.</p>
      <b>File > New > Import Module</b>
      <br>
      <img src="http://www.truiton.com/wp-content/uploads/2015/02/Android-Studio-Add-Library-1.jpg">
      <br>
      <p>En la ventana <b>"New Module"</b> seleccionar el directorio del modulo a importar, seleccionar el checkbx y remplazar el nombre del modulo con <b>":opencv-java"</b></p>
      <br>
      <img width=460 height=330 src="http://1.bp.blogspot.com/-XvGQFhswm4g/VayawVHvdFI/AAAAAAAAIFM/OCFoxD2l6h0/s1600/quan404_hinh5_new%2Bmodule.png">
  <li> <h4>Agregar dependencias</h4>
      <p>Para que el modulo sea reconocido por el nuevo proyecto tenemos que ingresarlo en dependencias, <b>Android Studio</b> maneja un archivo <b>build.gradle</b> para declararlas, agregaremos la siguiente linea dentro de la seccion dependencies.
      <br>
      <b>compile project(':opencv-java')</b>
      <br>
      <br>
      <img width=460 height=330 src="http://4.bp.blogspot.com/-PL5tJP1uflU/VayawuvY8KI/AAAAAAAAIFI/FnLvsFmL2uE/s1600/quan404_hinh6_gradle.png">
  <li> <h4>Agregar jniLibs</h4> 
</ol>
