# Práctica Git 2: Generación de un conflicto en git y fichero .gitignore

![Primera Imagen](/img/img1.png)

- Creamos el repositorio local, el index.html y hacemos commit con los cambios.

![Segunda Imagen](/img/img2.png)

- Creamos y nos movemos a la rama-1 y hacemos un commit con el nombre de pila añadido al index.html.

![Tercera Imagen](/img/img3.png)

- Volvemos a la rama principal, creamos y nos movemos a la rama-2 y agregamos el apellido al index.html.

![Cuarta Imagen](/img/img4.png)

- Vemos de forma resumina y gráfica el estado del repositorio.

![Quinta Imagen](/img/img5.png)

- Vemos el conflicto que se ha producido en el index.html. Nos muestra los cambios realizados en la rama actual y en la que estamos intentando mergear y nos da la opción de elegir qué cambios queremos conservar, también podemos mantener ambos, que es lo que voy a hacer en este caso.

![Sexta Imagen](/img/img6.png)

- Confirmo el merge después de arreglar el conflicto y muestro de forma gráfica el estado del repositorio.

![Septima Imagen](/img/img7.png)

- Cambiamos a master y mergeamos la rama-1 donde ya habíamos mergeado la rama-2, se hace un fast forward porque esta rama no había avanzado desde que se separarón las ramas.

![Octava Imagen](/img/img8.png)

- Borramos las ramas

![Novena Imagen](/img/img9.png)

- Copiamos nuestro repositorio al remoto del ejercicio.