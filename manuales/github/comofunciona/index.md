# Cómo funciona GitHub

GitHub puede parecer, a priori, un poco intimidante, pero nada más lejos si se se siguen unos pasos concretos.

Lo más importante es que te hayas creado una cuenta en GitHub. Si todavía no lo has hecho, puedes [ir al apartado del manual en el que se explica cómo crear una cuenta en GitHub](https://es.wordpress.org/team/handbook/manuales/github/crear/).

Si ya tienes una cuenta, puedes continuar en este camino.

## Qué es un repositorio

Llamamos _repositorio_ a un lugar que se podría comparar con una unidad de disco duro o una carpeta principal de un servidor. Endefinitiva, un lugar de almacenamiento de archivos.
 
En este _repositorio_ se pueden almacenar todo tipo de archivos, desde carpetas y ficheros sin un orden concreto, un programa completo o un manual como el que estás leyendo ahora mismo, que fue escrito en GitHub antes de ser publicado en la web.

## Acceder al repositorio de WordPress España

Para acceder al repositorio de WordPress, no tienes más que acceder a través de la siguiente dirección:

[https://github.com/WordPress/spain-handbook](https://github.com/WordPress/spain-handbook)

En este repositorio están alojados todos los archivos que conforman todo el manual de WordPress en español.

Aquí es donde vas a hacer todos los cambios que, una vez aceptados, se reflejarán en la esta web que estás leyendo.

Una vez registrados podemos acceder a la página principal de [GitHub](https://github.com/) y en la barra lateral aparecerá el listado de repositorios a los que tenemos acceso.

Pinchamos en [WordPress/spain-handbook](https://github.com/WordPress/spain-handbook) para acceder al repositorio de manuales de WordPress España. En la parte superior izquierda podremos ver en todo momento en qué repositorio estamos.

Con el fin de evitar posibles errores o conflictos **es importante no trabajar nunca directamente en este repositorio principal**. Para poder editar con seguridad, crearemos una copia del repositorio principal (*fork*) que será donde trabajaremos.

## Crear un fork

Crearemos el *fork* pinchando en el último botón que aparece en la parte superior derecha, está rodeado en azul para que puedas localizarlo más fácilmente.

[Realización Fork] ![Captura de pantalla 2024-03-24 114046](https://github.com/pilargarciaab/spain-handbook/assets/157137447/65193c12-2610-4d55-b9f3-dc19c46cc86d)


Después de realizarlo, la ventana cambiará y si nos fijamos en la ruta que se muestra en la parte de arriba a la izquierda ya aparecerá nuestro nombre de usuario, desde este momento cualquier cambio que hagamos en este repositorio, no afectará al repositorio original hasta que no hagamos un *Pull request* (solicitud de revisión) y éste no sea verificado y aprobado.

![Fork realizado](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/ForkRealizado.PNG)

## Sincronizar nuestra copia con el repositorio original

### Fetch upstream {#fetch}

**Si nuestro *fork* deja de estar actualizado**

Cuando se trabaja en un _fork_, se trabaja paralelamente al repositorio principal (wordpress/spain-handbook) en tu cuenta de github (micuenta/spain-handbook). 

Por tanto es posible que, mientras estés trabajando, otros contribuidores estén haciendo lo mismo en sus respectivos forks y hayan mandado los cambios al repositorio principal. Esos cambios no se aplicarán en tu fork mientras no sincronices tu repositorio con el principal.

De hecho, verás un mensaje como el siguiente:

`This branch is 8 commits behind WPES:master`

Significa que se han realizado 8 modificaciones desde que hicimos nuestra copia (*fork*).

A continuación un ejemplo del aviso:

![branch-outdated](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/branch-outdated.png)

En este caso, si el archivo principal se ha adelantado a nuestra versión, tenemos dos opciones: *Contribute* o *Fetch upstream*

Si ya hemos editado nuestro archivo, pulsaremos *Contribute*, aparecerá una pequeña ventana que indica que el archivo no está actualizado y nos invita a hacer un *Pull request* para fusionar nuestra edición con el archivo principal (*master*).

![contribute](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/contribute.png)

Si no hemos realizado aun cambios en nuestro *fork*, para trabajar en la versión aceptada más actualizada del archivo principal (*master*), podemos pulsar en *Fetch Upstream*, que nos dará a su vez dos opciones más: *Compare* o *Fetch and merge*

![fetch-upstream](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/fetch-upstream.png)

*Compare* nos permite comparar las distintas versiones que se han creado y *Fetch and merge* sincronizará nuestro *fork* con el archivo principal (*master*).

En cualquier caso, si hubiera algún conflicto entre ambas versiones, el sistema nos avisará y nos invitará a hacer antes un *Pull request*.

A continuación una imagen de lo que nos mostraría la opción *compare*:

![Comparing-changes](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/Comparing-changes.png)

## Seleccionar un Issue

## Crear una rama

## Editar un contenido



## Enviar un contenido

## Crear un Pull Request

Cuando terminamos de editar nuestro archivo podemos proceder a realizar un *pull request*, nuestro archivo se enviará al administrador para su revisión y, una vez realizadas las comprobaciones pertinentes, nuestro *fork* se fusionará con el archivo principal.

Para hacer *pull request* a partir de nuestro *fork*:

1. Ir al repositorio principal y una vez allí, pulsar en *Pull requests*.

![pull-request-1](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/pull-request-1.png)

2. En pantalla aparecerá un listado con los *pull requests* existentes en ese momento (si los hay), para crear el nuestro pulsaremos en *New pull request*.

![pull-request-2](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/pull-request-2.png)

3. En este paso tenemos la oportunidad de comparar el archivo principal con nuestra propuesta, como en nuestro caso lo estamos haciendo desde un *fork*, pulsaremos *compare accross forks*, puesto que necesitamos indicar qué dos archivos vamos a comparar.

![pull-request-3](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/pull-request-3.png)

4. Nos aparecerá un nuevo encabezado en el que podremos seleccionar nuestro *fork* pulsando en el desplegable *head repository*.

![pull-request-4](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/pull-request-4.png)

5. Si no hay ningún conflicto entre ambas versiones, el sistema nos indicará *Able to merge*, lo que significa que ya podemos pulsar la opción *Create pull request*.

![pull-request-5](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/pull-request-5.png)

6. En la siguiente pantalla aparecerá una ventana con los campos *Title* para poner un título a nuestra propuesta y *Write* para añadir los comentarios necesarios.

Es imprescindible rellenar el campo *Title* para que se habilite la opción *Create pull request*, de lo contrario, la selección permanecerá deshabilitada.

![pull-request-6](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/pull-request-6.png)

7. Cuando terminamos de rellenar los campos, pulsamos sobre *create pull request* y se abre un desplegable con dos opciones como vemos en la siguiente imagen.

Dejaremos seleccionada la primera opción si nuestro archivo ya está listo para revisión.

![pull-request-7](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/pull-request-7.png)

