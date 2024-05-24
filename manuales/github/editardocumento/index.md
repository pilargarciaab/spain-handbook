# Editar un documento/archivo

## Editar un contenido

### Abrir la sesión de edición

Una vez creado nuestro *fork* y creada la rama sobre la que vamos a trabajar, podemos proceder a editar el archivo, para ello pulsaremos el icono en forma de lápiz.

![editar archivo](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/editar-archivo.png)

### Validar los cambios de edición

Al terminar la edición, para guardar los cambios, debemos ir al final de la página, rellenar los campos correspondientes a *commit changes* y pulsar *Commit changes*.

Si queremos añadir los cambios en nuestro *fork*, dejaremos seleccionada la opción "*Commit directly to the master branch.*". De lo contrario estaríamos creando una nueva rama a partir de nuestro *fork*.

![commit changes](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/commit-changes.png)

### Inserción de imágenes

Para insertar imágenes en el manual, éstas se subirán a la carpeta **assets** que se encuentra en la misma carpeta donde está el documento donde se va a insertar dicha imagen.

A continuación, se referenciará la imagen con el comando correspondiente de *Markdown*, como se muestra a continuación:

```
![Texto alternativo](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/imagen.jpg)
```

Se muestra a continuación un ejemplo en el que la imagen quedará de la siguiente forma:

![Ejemplo de cómo queda la imagen en el editor](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/ejemplo-imagen-insertada.jpeg)

Lo más importante es que hay que subir la imagen a la carpeta **assets** que se encuentre en la misma carpeta que el documento que se esté editando en ese momento. Para ello, hay que hacer clic sobre dicha carpeta hasta que veamos los archivos que hay dentro.

![Carpeta a la que hay que subir la imagen](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/insertar-imagen-01.jpeg)

A continuación, hay que hacer clic en el botón *Add file*, del que se desplegará un submenú. A continuación hay que hacer clic en el botón *Upload files*. De esta forma, aparecerá la página de subida de imágenes.

![Botón subir imagen](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/insertar-imagen-02.jpeg)

Para subir la imagen es suficiente arrastrarla desde el ordenador hasta el área habilitada para ello, en la que indica el mensaje **Drag additional files herre to add them to your repository**. También se puede subir a través del enlace **choose your files**.

Una vez subida la imagen, hay que rellenar la descripción del **commit** para aclarar de qué se trata la imagen, y finalmente habrá que hacer clic en el botón **commit changes**.

![Pantalla de subida de imagen](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/insertar-imagen-03.jpeg)

Por último, para insertar la imagen en el texto, se usará el código **markdown** visto anteriormente. Por ejemplo, la imagen con la que se ha iniciado este ejemplo se llama **1.AltaGitHub.png**, y el texto alternativo que se le ha añadido es "Alta cuenta Github". Por tanto, el código utilizado es el que se muestra en la siguiente imagen.

![Código markdown para mostrar la imagen en el texto](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/github/assets/insertar-imagen-04.jpeg)

El resultado será el que se muestra al principio de este apartado.

![Manual de Markdown ](https://raw.githubusercontent.com/WPES/spain-handbook/master/manuales/markdown/index.md)

![Manual de Edicion de imagenes](https://github.com/WordPress/spain-handbook/blob/main/manuales/github/editarimagen/index.md)
