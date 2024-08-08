# Café Agere

Este es un proyecto web para la tienda **Café Agere**, una tienda especializada en variedades de café y accesorios relacionados. Este repositorio contiene el código fuente del sitio web, incluyendo el HTML, CSS y SCSS utilizados para construir la interfaz de usuario.

## Índice

- [Café Agere](#café-agere)
  - [Índice](#índice)
  - [Descripción](#descripción)
  - [Estructura del Proyecto](#estructura-del-proyecto)
    - [Descripción de Carpetas](#descripción-de-carpetas)
  - [Tecnologías](#tecnologías)
  - [Instalación](#instalación)
  - [Uso](#uso)
  - [Contribuciones](#contribuciones)
  - [Licencia](#licencia)

## Descripción

El proyecto **Café Agere** tiene como objetivo proporcionar una experiencia de usuario intuitiva y atractiva para los visitantes de la tienda en línea. La web está diseñada para resaltar las diferentes variedades de café, accesorios disponibles, y las ubicaciones físicas de la tienda.

## Estructura del Proyecto

El proyecto sigue el patrón 7-1 de Sass para organizar el código SCSS:

```bash
├── assets
│ ├── css
│ │ └── main.css
│ ├── img
│ │ └── (imágenes usadas en el proyecto)
│ └── scss
│ ├── abstracts
│ │ └── _mixins.scss
│ ├── base
│ │ ├── _base.scss
│ │ └── _reset.scss
│ ├── components
│ │ ├── _boxes.scss
│ │ └── _cards.scss
│ ├── layout
│ │ └── _header.scss
│ ├── pages
│ │ └── _home.scss
│ └── main.scss (archivo principal que importa todos los parciales)
├── index.html
└── README.md
```


### Descripción de Carpetas

- **abstracts**: Contiene mixins, funciones y variables que se usan en todo el proyecto.
- **base**: Incluye estilos globales, como el reset y las reglas base.
- **components**: Contiene estilos específicos para componentes reutilizables como cajas y tarjetas.
- **layout**: Estilos para el diseño general, como el header.
- **pages**: Estilos específicos para páginas individuales, como la página principal (home).

## Tecnologías

Este proyecto utiliza las siguientes tecnologías:

- **HTML5**: Estructura del contenido.
- **CSS3**: Estilos y presentación visual.
- **Sass (SCSS)**: Preprocesador de CSS para mejorar la organización y mantenimiento del código.
- **Google Fonts**: Tipografía utilizada en el proyecto.

## Instalación

1. **Clona este repositorio:**

```bash
git clone https://github.com/mr-gantiva/cafe-agere.git
```

2. **Navega al directorio del proyecto:**
   
```bash
cd cafe-agere
```

3. **Instala las dependencias (si es necesario):**
   
Este proyecto no tiene dependencias de Node.js o similares. Los archivos CSS generados están incluidos.

## Uso

1- Abre el archivo index.html en tu navegador para ver el proyecto en acción.
2- Para modificar los estilos:

- Edita los archivos SCSS en la carpeta assets/scss/.
- Compila los archivos SCSS a CSS utilizando tu compilador de Sass preferido.
  
## Contribuciones
¡Las contribuciones son bienvenidas! Si tienes alguna mejora, sugerencia o reporte de errores, por favor abre un "issue" o envía un "pull request".

## Licencia
Este proyecto está bajo la Licencia MIT. Puedes ver más detalles en el archivo LICENSE.
