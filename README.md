# TGF_Plataforma_Caracterizacion
Programas utilizados para la realización de una plataforma flexible de caracterización de sensores táctiles. La estructura de este repositorio se divide en dos carpetas según el programa usado :
##LabVIEW
Dentro de esta carpteta se incluye el programa principal llamado "Interfaz_Completa.vi". Además se incluye una librería .llb que contiene todos los subVI creados para el programa principal. Sin esta librería el programa principal no puede ejecutarse. 
Se añade también un archivo .txt (dentro de la carpeta "Sesiones") donde se guardan las sesiones que el usuario cree. Este archivo solo cuenta con la sesión Dafault, la cual no puede borrarse bajo ningún caso para asegurar un buen funcionamiento.
##PSoC
Contiene la programación realizada en el programa "PSoC Creator 4.4". Se divide en dos carpetas, una contiene el workspace y el proyecto del esclavo y otra contiene esta misma información pero para el maestro. 

