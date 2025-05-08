# Página Web Responsive - Evaluación Módulo 1

Este proyecto consiste en la creación de una página web responsive a partir de un diseño proporcionado. Se ha desarrollado utilizando HTML, Sass y metodologías modernas de maquetación como Flexbox, CSS Grid, media queries y pequeñas animaciones con transiciones. Este ejercicio forma parte de la evaluación final del Módulo 1 del curso de Desarrollo Web de Adalab.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Funcionalidades](#funcionalidades)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura de carpetas](#estructura-de-carpetas)
- [Créditos](#créditos)
- [Notas adicionales](#notas-adicionales)

---

## 📄 Descripción

El proyecto consiste en la maquetación de una landing page responsive basada en diseños proporcionados a través de Zeplin. Se han respetado las estructuras visuales, secciones y comportamiento esperados para distintos tamaños de pantalla. La web incluye enlaces, estilos dinámicos con transiciones y una organización clara del contenido utilizando técnicas de diseño actuales.

## ✨ Funcionalidades

- Menú hamburguesa fijo con enlace a la página de Adalab.
- Módulo **Hero** a pantalla completa con fondo y botón de flecha que enlaza a otra sección.
- Módulo **Tu tienda de deporte** con diseño adaptable.
- Módulo **Vuelta al cole** maquetado con Flexbox.
- Footer maquetado con CSS Grid y con enlaces reales a Adalab.
- Scroll interno mediante anclas en los botones de flecha.
- Efectos de `hover` en botones.

## 🛠️ Tecnologías utilizadas

- **HTML5**: Estructura semántica del sitio web.
- **Sass**: Organización del CSS con parciales, anidación y variables.
- **Flexbox**: Distribución de elementos en secciones como el hero o la sección de productos del tercer módulo.
- **CSS Grid**: Maquetación del footer.
- **Media Queries**: Diseño responsive adaptado a diferentes resoluciones de pantalla.

## 💻 Instalación y uso
> ⚠️**NOTA:** Necesitas tener instalado [Node JS](https://nodejs.org/) con una versión superior a la 14 para trabajar con este proyecto.

1. Clona este repositorio:
```bash
git clone [URL-del-repositorio]
```
2. Navega a la carpeta del proyecto:
```bash
   cd nombre-del-repositorio
```
3. Instala las dependencias:
```bash
npm install
```
4. Inicia el servidor de desarrollo:
```bash
npm run dev
```
5. Compilar para producción
```bash
npm run build
```
Los archivos optimizados se generarán en la carpeta `docs/`.
6. Despliege en GitHub Pages.
Entra en la pestaña `settings` de tu repo y en el apartado de GitHub Pages activa la opción **master branch /docs folder**.

Atajo:
```bash
npm run deploy
```
Genera la versión de producción y hace push de la carpeta `docs/` del tirón.


## 📂 Estructura de carpetas

```
📁 docs/
│   ├── assets/            # Archivos estáticos generados (JS, CSS optimizados)
│   ├── images/            # Imágenes optimizadas al compilar
│   ├── js/
│   │   └── main.js        # JS compilado para producción
│   └── index.html         # HTML compilado final

📁 public/
│   └── images/            # Imágenes públicas

📁 src/
│   ├── js/               # Archivo principal de JavaScript
│   │    └── main.js
│   ├── partials/          # Fragmentos HTML para reutilizar con `vite-plugin-html-inject`
│   │   ├── header.html
│   │   ├── footer.html
│   │   ├── main.html
│   │
│   ├── scss/              # Estructura modular para estilos SCSS
│   │   ├── components/
│   │   ├── core/
│   │   ├── layout/
│   │   └── main.scss      # Punto de entrada SCSS
│   └── index.html         # Archivo HTML principal

```

## 🧑‍💻 Créditos
Este proyecto ha sido desarrollado por Idoia Belloso Elola como parte de la evaluación final del Módulo 1 del curso de Adalab.

Recursos proporcionados por Adalab:
- Starter Kit
- Diseños en Zeplin
- Imágenes e iconos
- Enunciado del ejercicio

