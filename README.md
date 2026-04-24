# 🎬 Disney UI Clone (Vanilla CSS + HTML)

## 📌 Descripción
Este proyecto es una réplica de una interfaz estilo Disney, desarrollada con **HTML5 semántico y CSS3 puro**, aplicando buenas prácticas de arquitectura frontend moderna como:

- Metodología **BEM**
- Layout con **CSS Grid + Flexbox**
- Diseño **Mobile-First**
- Sistema de variables CSS (`:root`)
- Componentes reutilizables
- Diseño responsive (mobile, tablet, desktop)

---

## 🚀 Tecnologías usadas

- HTML5 semántico
- CSS3 puro (sin frameworks)
- Google Fonts (Montserrat)
- CSS Grid
- Flexbox
- Media Queries

---

## 🧱 Arquitectura del proyecto


/project
│── index.html
│── styles.css
│── assets/
│ ├── banner-background.jpg
│ ├── snow-white.png
│ ├── shop-image-1.jpg
│ ├── shop-image-2.jpg
│ ├── shop-image-3.jpg
│ ├── shop-image-4.jpg
│ ├── disney-plus-1.jpg
│ ├── disney-plus-2.jpg
│ ├── disney-plus-3.jpg
│ ├── movies-1.jpeg
│ ├── movies-2.jpeg
│ ├── movies-3.jpeg
│ ├── movies-4.jpeg
│ ├── movies-5.jpeg
│ ├── disney-parks-1.jpg
│ ├── disney-parks-2.jpg
│ └── more-background.jpg


---

## 🎨 Sistema de diseño

Se implementó un sistema de variables CSS para consistencia visual:

```css
:root {
  --color-primary: #e62429;
  --color-bg-shop: #f5c542;
  --color-bg-dark: #0b1d2a;
  --color-text-dark: #111;
  --color-text-light: #fff;
}
🧩 Componentes principales
🧭 Header
Sticky con backdrop-filter
Layout flexible con Flexbox
Navegación responsive
🎯 Hero Section
Imagen de fondo full screen
Overlay de contenido
Logo superpuesto
CTA button
🧱 Cards System
Hover effects con transform: scale()
Shadow dinámico
Border radius consistente
🔘 Buttons

Sistema reutilizable:

.btn (base)
.btn--red
.btn--outline
.btn--pill


Arquitectura limpia
Responsividad real
Componentización CSS
Escalabilidad del diseño
📌 Posibles mejoras futuras
Animaciones (scroll reveal + parallax)
Lazy loading de imágenes
Dark mode toggle
Conversión a React components
Optimización de performance (Lighthouse 90+)
👨‍💻 Autores

* Erika Andrea Erazo Rodriguez
* Diogenes Bermeo Sanchez 

Proyecto educativo de práctica frontend 