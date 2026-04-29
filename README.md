# Carrusel Anaglifo 3D 🎞️

Proyecto básico en **HTML + CSS + Bootstrap 5** que muestra un carrusel de imágenes anaglifo.

---

## 🚀 Tecnologías utilizadas
- **HTML5**
- **CSS3** (archivo separado en `assets/css/styles.css`)
- **Bootstrap 5** (CDN)

---

## ⚙️ Funcionalidad
- Carrusel automático que cambia cada 3 segundos.
- Controles de navegación (anterior y siguiente).
- Navbar superior con título.
- Footer fijo en la parte inferior de la pantalla.

---

## 🎨 Personalización
En el archivo `assets/css/styles.css` puedes ajustar:

```css
/* Carrusel más grande y centrado */
.carousel {
  max-width: 900px;   /* ancho máximo */
  margin: 0 auto;     /* centrado */
}

/* Imágenes del carrusel */
.carousel-item img {
  height: 500px;       /* altura fija */
  object-fit: contain; /* mantiene proporciones */
}

/* Footer fijo */
footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: #212529;
  color: white;
  text-align: center;
  padding: 10px;
}

/* Espacio para que el contenido no quede oculto */
body {
  padding-bottom: 60px;
}
