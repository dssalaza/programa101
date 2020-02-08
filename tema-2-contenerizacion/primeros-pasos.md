# Primeros Pasos

Vamos a lanzar nuestro contenedor y luego vamos a ir explicando paso a paso que significa el comando y sus parámetros; manos a la obra!, abre tu terminal y ejecuta el siguiente comando

```text
docker run -d -p 80:80 dockersamples/101-tutorial:es
```

Felicitaciones! Ha iniciado el contenedor para este tutorial! Primero vamos a explicar el comando que acabas de ejecutar.

Notarás que se están usando algunos parámetros. Aquí hay más información sobre ellos:

* `-d` - ejecuta el contenedor en modo independiente \(tarea de fondo o segundo plano\).
* `-p 80:80` - asigna el puerto 80 del host al puerto 80 del contenedor
* `dockersamples/101-tutorial` - la imagen a utilizar especificando
* `:es -` Aunque no es estrictamente un medio para identificar un contenedor, esto nos permite  especificar una versión de una imagen con la que te gustaría ejecutar el contenedor `image[:tag]` en este caso vamos a usar la versión español

{% hint style="info" %}
**Consejo**

Puede combinar parámetros de un solo carácter para acortar el comando completo. Por ejemplo, el comando anterior podría escribirse como:

`docker run -dp 80:80 dockersamples/101-tutorial:es`
{% endhint %}

