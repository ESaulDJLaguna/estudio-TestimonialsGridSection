# Testimonials Grid Section

Solución del [ejercicio propuesto](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7) en [Frontend Mentor](https://www.frontendmentor.io).

![Desktop preview](images/desktop-preview.jpg)

## Resultado final del proyecto

https://testimonials-grid-section-frontend-mentor.netlify.app/

## Extensiones y dependencias

Para hacer modificaciones al proyecto se requiere de las siguientes extensiones en *Visual Studio Code*:

1. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). No es obligatoria. Permite visualizar en tiempo real los cambios hechos en la página.
2. [JS & CSS Minifier(Minify)](https://marketplace.visualstudio.com/items?itemName=olback.es6-css-minify). Usada para crear el CSS minificado.
3. [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass). Utilizada para compilar el archivo *custom.scss*.
4. [PurgeCSS](https://purgecss.com/). Herramienta utiizada para elimiar código CSS que no se está utiizando. Es obligatoria para hacer uso del comando `npm run build`. Para instarlo se utiliza:

~~~
npm install -g purgecss
~~~

## Cómo realizar modificaciones

1. Clonar el repositorio y acceder al proyecto:

~~~
$ git clone https://github.com/ESaulDJLaguna/testimonials-grid-section.git
$ cd testimonials-grid-section
~~~

2. Instalar las dependencias:

~~~
$ npm install
~~~

3. Crear una carpeta en el proyecto principal llamada *css*.
4. Abrir el archivo `custom.scss` dentro de la carpeta *sass* para comenzar a editar los estilos. En este punto debe activarse la extensión *Live Sass Compiler*, en seguida, se procede a editar con un espacio, un enter, una letra, etc. y a eliminar dicho elemento extra, de esta forma, una vez que se guarde el archivo `custom.scss`, la extensión observará los cambios y creará el archivo `custom.css` dentro de la misma carpeta.
5. Ejecutamos el comando `npm run build`. Esto creará el archivo *reducido.css* dentro de la carpeta *css*.
6. Finalmente, utilizando la extensión *JS & CSS Minifier(Minify)*, para minificar el archivo creado en el punto anterior.

> **Cada vez que se realiza un nuevo cambio en los estilos, deben hacerse los pasos 5 y 6.**