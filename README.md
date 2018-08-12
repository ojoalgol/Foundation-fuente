# Frontend Desing con Foundation y PostCSS
## Ejercicio

La idea de este ejercicio es que aprendamos a trabajar con uno de los frameworks (entorno de trabajo o marco de trabajo) para el diseño frontend (interfaz) más utilizados en la industria actualmente, como lo es Foundation.

Lo que me motivó en este caso es la poca documentación en español que hay sobre esta interesante herramienta.

### Herramientas utilizadas
* HTML5
* CSS3
* JS
* Foundation
* Foundation Icons
* Font Awesome
* **Gulp** (Automatización de tareas)
	- browser-sync: sirve como base para el servidor de desarrollo, y sincroniza nuestro navegador con los cambios que hacemos.
	- css-mqpacker: para unificar las media-queries de nuestro proyecto, lo cual es muy útil para no tener código repetido en nuestro fichero css final.
	- rucksack-css: crea una tipografía fluida automática con una nueva propiedad responsive en font-size.
	- gulp-file-include: podemos crear archivos parciales de HTML en nuestro proyecto, lo cual permite reutilizar código y agilizar el trabajo.

* **Postcss** (gulp-postcss para procesamiento de CSS)
	- postcss-mixins: para reutilizar estilos de CSS.
	- postcss-import: para importar archivos CSS dentro de otros archivos CSS. Debemos tener cuidado de no hacer “require” usando la palabra reservada “import” (la cual es usada por JS), para este caso usamos: atImport.
	- postcss-nested: extienden la sintaxis de CSS; similar a SASS y Stylus, cómo por ejemplo, la posibilidad de anidar clases.
	- postcss-cssnext: es un complemento que ayuda a utilizar la última sintaxis de CSS en la actualidad. Transforma las nuevas especificaciones de CSS en CSS más compatibles para que no tenga que esperar al soporte del navegador. 
	- csswring: Es un minificador de CSS para PostCSS. Es importante que vaya al último para que no tenga conflictos.   

### Equipo
* [Enrique J. Valerio G. (Cursante)](https://github.com/Caballero73 "Enrique Valerio - Cursante")