# Cambios realizados por Daniel García Ayala
Los cambios realizados han sido simples, comencemos con los textos.

## Textos cambiados
Para ello lo realizado fue indagar en el [archivo strings.xml](https://github.com/fregonaespanola/MaterialThemeBuilder/blob/master/app/src/main/res/values/strings.xml) comparando los textos mostrados 
dentro de dicho archivos con los textos de la propia app al ejecutarla. Una vez ya comparados y sabiendo
a que hace referencia cada uno, procedí a cambiarlos como se puede ver en esta captura.

![IMAGEN DE TEXTOS](./img/2.PNG)

## Colores cambiados
Para los colores se realizaron dos cambios importantes, los cambios para el modo diurno y los cambios para el
modo oscuro.

Para el modo diurno procedí a realizar cambios en [values/themes.xml](https://github.com/fregonaespanola/MaterialThemeBuilder/blob/master/app/src/main/res/values/themes.xml) para cambiar el aspecto general de la aplicación,
es decir, los colores primarios y secundarios para la misma.
Seguidamente en [values/colors.xml](https://github.com/fregonaespanola/MaterialThemeBuilder/blob/master/app/src/main/res/values/colors.xml) también se realizaron cambios pero estos afectarían a ambos modos.

![IMAGEN DE COLORES DIURNOS](./img/3.PNG)

Para el modo nocturno, ví que existía una caperta llamada [values-night](./app/src/main/res/values-night/themes.xml) la cual contenía un archivo themes.xml el cual
era igual que el diurno así que procedí a realizar los cambios.

![IMAGEN DE COLORES NOCTURNOS](./img/4.PNG)

## Ramas

La única rama existente es master así que todos los cambios están realizados ahí.

## Datos para subirlo a GitHub

Por un error que desconozco no me dejaba hacer el commit desde Android Studio por lo que se tuvo que realizar
de la siguiente manera.

1. Hacer el add desde el AndroidStudio.
2. Hacer el commit desde la terminal Git Bash.
3. Volver al AndroidStudio para poder realizar el push mediante el link del repositorio.