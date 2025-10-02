# Landing Page Moderna para Gimnasio

Sitio web responsive, moderno y optimizado para SEO. Incluye Home, Servicios y Contacto, usando HTML5, SCSS (Sass), Bootstrap 5 y CSS puro.

---


## 🚀 Funcionalidad y características

- Landing page profesional para gimnasio, fitness o wellness.
- 100% responsive y mobile-first.
- Navegación sticky y header fijo.
- Secciones: Hero (con imagen de fondo y overlay), Servicios (cards limpias y modernas), Galería (imágenes cuadradas de fondo), Testimonios, Contacto.
- Cards de servicios sin imágenes, solo texto y estilos modernos.
- Galería con imágenes de fondo cuadradas, adaptables.
- Formulario accesible y validado.
- Íconos de redes sociales (Bootstrap Icons).
- Optimización SEO: meta tags, titles, descriptions y estructura semántica.
- Paleta de colores personalizada (escala de azules y grises, ver abajo).

---


## 📁 Estructura de Carpetas y Archivos

```
project-root/
 ├── index.html
 ├── servicios.html
 ├── contacto.html
 ├── /scss
 │    ├── _variables.scss
 │    ├── _header.scss
 │    ├── _home.scss
 │    ├── _servicios.scss
 │    ├── _contacto.scss
 │    └── style.scss
 ├── /css
 │    └── style.css
 ├── /images
 │    ├── galeria1.jpg ... galeria6.jpg (galería)
 │    ├── servicio1.jpg ... servicio5.jpg (opcional, no usados en cards)
 ├── /js
 │    └── main.js
 └── README.md
```

---


## 🔎 Estructura SEO implementada

- Meta tags: charset, viewport, description, keywords, author.
- Titles y descriptions únicos por página.
- Uso de etiquetas semánticas: `<header>`, `<nav>`, `<section>`, `<footer>`.
- Imágenes con `alt` descriptivo.
- Navegación accesible y enlaces claros.
- Carga de fuente Roboto desde Google Fonts.

---


## 🎨 Personalización y configuración

### 1. Paleta de colores (en `scss/_variables.scss`)

```scss
$color-blue-dark: #10403B;    // Azul petróleo profundo
$color-blue-main: #127369;    // Azul/verde oscuro
$color-blue-light: #8AA6A3;   // Azul claro/grisáceo
$color-blue-gray: #4C5958;    // Gris azulado
$color-gray-light: #BFBFBF;   // Gris claro
$color-bg: #BFBFBF;           // Fondo general gris claro
$color-section: #8AA6A3;      // Fondo de secciones destacadas
```

### 2. Imágenes
- Galería: usa galeria1.jpg en `/images`.
- Cards de servicios: solo texto, no usan imágenes.
- Puedes cambiar las imágenes de galería por las de tu negocio.

### 3. Contenido
- Edita los textos y servicios en los archivos HTML.
- Personaliza testimonios y datos de contacto.

### 4. SCSS y estilos
- Escribe tus estilos en los partials SCSS correspondientes.
- Compila el SCSS a CSS (puedes usar VSCode con la extensión Live Sass Compiler o el comando `sass`):
  ```
  sass scss/style.scss css/style.css --watch
  ```

### 5. Bootstrap y JS
- Bootstrap y Bootstrap Icons se cargan por CDN.
- Puedes agregar scripts propios en `/js/main.js`.

---


## 📝 Notas y recomendaciones

- El código está comentado para facilitar la edición.
- El formulario es accesible y usa labels.
- Puedes ampliar la galería, servicios o testimonios según tus necesidades.
- Recuerda optimizar las imágenes para web.
- Si cambias la paleta, revisa que todos los colores usados en los SCSS existan en `_variables.scss`.
- Si usas imágenes en cards de servicios, deberás ajustar el HTML y los estilos.

---


## 👨‍💻 Créditos

- Diseño y desarrollo: Enrique Alegre
- Imágenes: Unsplash
- Frameworks: Bootstrap 5, Bootstrap Icons, Google Fonts

---


