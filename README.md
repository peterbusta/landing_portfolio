# PFO1 - Landing Page de Portafolio

Proyecto individual correspondiente a la **Práctica Formativa Obligatoria 1 (PFO1)** de Desarrollo Web Front-End. Se trata de una página de aterrizaje (landing page) que presenta mi perfil profesional, áreas de especialización, habilidades técnicas, secciones personales y un canal directo de contacto.

## 🚀 Despliegue (Demo en vivo)
- **URL de producción (Vercel):** [https://pmb-portfolio-one.vercel.app/](https://pmb-portfolio-one.vercel.app/)
- **Repositorio de GitHub:** [https://github.com/peterbusta/landing_portfolio](https://github.com/peterbusta/landing_portfolio)

---

## 🛠️ Tecnologías y Requisitos Técnicos Implementados
- **HTML5 Semántico:** Estructuración mediante etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<form>`, `<label>`).
- **CSS3 Moderno:**
  - Variables CSS (`:root`) para consistencia en la paleta de colores y estilos globales.
  - Maquetación híbrida con **Flexbox** (navegación, encabezado de presentación, formularios) y **CSS Grid** (grillas de habilidades y tarjetas de experiencia/intereses).
  - **Diseño Responsive:** Adaptabilidad fluida a resoluciones móviles y de escritorio mediante `clamp()`, unidades relativas y `@media queries`.
  - **Transiciones:** Microinteracciones y estados dinámicos (`transition: 0.2s ease`) en enlaces, botones e inputs.
- **Tipografía:** Integración externa vía Google Fonts con las familias *Inter* (texto principal) y *Poppins* (encabezados).
- **Accesibilidad:** Uso de atributos `alt` descriptivos en imágenes, etiquetas `<label>` vinculadas con `id` en el formulario y atributos `aria-label` en secciones clave.

---

## 🎨 Decisiones de Diseño y Arquitectura
1. **Paleta y Modo Oscuro:** Se optó por una interfaz en tonos oscuros (fondo azul noche/grafito `#0f141c`) con acentos en amarillo ámbar (`#f59e0b`), priorizando la legibilidad y un aspecto técnico sobrio.
2. **Estructura Modular:** Organización limpia del contenido en bloques temáticos (Presentación con foto, Grilla de Habilidades por especialidad, Trayectoria/Intereses y Formulario de Contacto).
3. **Distribución en Sección Principal:** Disposición horizontal (foto a la izquierda y bloque de texto a la derecha ocupando el ancho disponible) que conmuta a vertical en dispositivos móviles.

---

## 📷 Registro de Recursos Visuales
- **Fotografía de perfil (`foto.jpg`):** Fotografía personal del autor utilizada como imagen de presentación.

---

## 🤖 Declaración de Uso de Inteligencia Artificial
- **Herramienta utilizada:** Gemini (Google).
- **Propósito:** Asistencia en la depuración de reglas CSS (Flexbox/Grid), estructura de layout responsive y verificación de cumplimiento de la consigna técnica.
- **Plan y metodología:** Se partió de una estructura inicial de HTML y CSS desarrollada por el autor. Se consultó al modelo para corregir el ordenamiento visual de la cabecera (alineación de foto a la izquierda y texto a la derecha) y optimizar el aprovechamiento del ancho.
- **Experiencia previa:** Conocimientos básicos e intermedios de maquetación web con HTML5 y estilos CSS.
- **Revisión y adaptación con criterio propio:** Se integraron las correcciones de nombres de clases y propiedades `flex` sugeridas, validando manualmente la jerarquía del DOM, la compatibilidad con las media queries preexistentes y la coherencia visual del sitio.
