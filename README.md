> # EcoStore whit Sass
by @juliangadev

## Descipción del proyecto
Es una pagina web responsive de una tienda ecologica cuenta con las secciones desarrollado con el preprocesador de css: **Sass**.

- **Header**, donde tenemos el navbar y el logo
- **Main section**, donde esta todo el contenido principal: Hero, productos, about us y location
- Y por ultimo el **Footer** donde tenemos los enlaces a redes sociales.

- Proyecto desplegado : https://ecostoresassjgl.netlify.app/

## Instalación de Sass
#### Instrucciones para instalar y configurar Sass mediante Node.js

1. Abre una terminal y navega hasta la carpeta raíz de tu proyecto.

Asegúrate de tener Node.js instalado en tu sistema. Puedes verificarlo escribiendo node -v en la terminal. Si no lo tienes instalado, ve al **[sitio web oficial](https://nodejs.org/en)** de Node.js para descargarlo e instalarlo.

2 . Ejecuta el siguiente comando para instalar Sass a nivel global:

```
npm install -g sass

```

3 . Ahora que tienes Sass instalado a nivel global, puedes compilar tus archivos Sass en CSS con el siguiente comando en la terminal:

```
sass input.scss output.css

```

4 . Reemplaza “input.scss” con la ruta y el nombre de tu archivo Sass, y “output.css” con la ruta y el nombre de tu archivo CSS de salida. Por ejemplo:

```
sass styles/main.scss styles/main.css

```

5 . Si quieres compilar automáticamente tus archivos Sass en CSS cada vez que hagas cambios, puedes usar la opción --watch:

```
sass --watch input.scss:output.css

```

6 . Si estás utilizando Node.js en tu proyecto, también puedes usar un paquete de npm llamado sass para compilar tus archivos Sass en CSS. Para instalarlo, ejecuta el siguiente comando:

```
npm install sass

```

7 . En tu archivo de configuración de Node.js (como package.json) agrega un script para compilar tus archivos Sass en CSS. Por ejemplo:

```
"scripts": {
  "build:css": "sass input.scss output.css"
}

```

8 . Ahora puedes ejecutar el script con el siguiente comando:

```
npm run build:css

```

Eso es todo. Con estas instrucciones deberías poder instalar y configurar Sass en tu proyecto de Node.js.
