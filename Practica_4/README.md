# Practica 4

## Video: <a href="https://www.youtube.com/watch?v=FgQgZcfQjoI">VIDEO DE PRACTICA 4</a>


Esta práctica consiste en en utilizar SonarQube para realizar algunas pruebas de calidad de codigo y poder ver los resultados y sugerencias para mejorar el codigo de un proyecto. Debido a que en la práctica 3 solo utilizamos una página web sin lenguaje de programación decidí utilizar uno de los proyectos utilizados en la Practica 2 en los que se utilizó .NET para analizar con SonarQube.

SonarQube se utilizó localmente, luego de descargar SonarQube se descargó el escaner utilizado para .NET 

<img src="https://snz04pap002files.storage.live.com/y4mNS9VJo_rAFzoRHRImc_tEvn1g3GCAl5wFAf8Kniv-gKFtQPmcWNReKQpD0tRPt5mU2o4LSnClqe9QHDAf1HhYyA8Gtjjm2g_9WzpFG0fR3x0Iq8fx8cq6pHmgf-iZ5MdfvgBhUWBmrTEcqC-4By1z1yvuiWs0X63ydSf0wy2cAZTSxSN5NAE3wW1Aq9XkSBC?width=726&height=827&cropmode=none" alt="SonarScanner" width="470"/>

Una vez en la consola, los comandos para realizar el escaneo son tres:

```
SonarScanner.MSBuild.exe begin /k:"ServicioRestaurante" /d:sonar.login="8ead54cad189d65e5c751167d129c11d78e10223"

MSBuild.exe D:\Documents\GitHub\LabSA2021_200714432\ServicioRestaurante /t:Rebuild

SonarScanner.MSBuild.exe end /d:sonar.login="8ead54cad189d65e5c751167d129c11d78e10223"
```

El resultado se puede observar en el panel de administracion de SonarQube

```
http://localhost:9000/
```
