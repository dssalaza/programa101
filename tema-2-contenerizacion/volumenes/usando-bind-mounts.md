# Usando Bind Mounts

En el capítulo anterior, hablamos y usamos un **volúmenes nombrados** para mantener los datos en nuestra base de datos. Los volúmenes nombrados son excelentes si simplemente queremos almacenar datos, ya que no tenemos que preocuparnos por _donde_ se almacenan los datos.

Con **bind mounts**, controlamos el punto de montaje exacto en el host. Podemos utilizar esto para persistir en los datos, pero a menudo se utiliza para proporcionar datos adicionales en contenedores. Cuando trabajamos en una aplicación, podemos usar bind mount para montar nuestro código fuente en el contenedor para que vea los cambios de código, responda y nos permita ver los cambios de inmediato.

Para aplicaciones basadas en Node, [nodemon](https://npmjs.com/package/nodemon) es una gran herramienta para observar los cambios en los archivos y luego reiniciar la aplicación. Existen herramientas equivalentes en la mayoría de los demás lenguajes y frameworks.

