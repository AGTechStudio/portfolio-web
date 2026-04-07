PORTFOLIO WEB – Alejandro García

Sitio web personal desarrollado como CV online y portfolio profesional.  
Incluye experiencia laboral, formación académica, habilidades técnicas y proyectos con demostraciones en video.

---

🚀 Demo

🔗 https://github.com/AGTechStudio/portfolio-web

---

📌 Descripción

Este proyecto es un sitio web responsive orientado a mostrar mi perfil profesional como:

- Technical Support
- IT Analyst
- Desarrollador de soluciones digitales

El objetivo es presentar de forma clara:

- Experiencia laboral
- Educación
- Skills técnicas
- Proyectos reales con video demo
- Información de contacto

---

🧩 Tecnologías utilizadas

- HTML5
- CSS3 (con variables y modo oscuro)
- JavaScript (vanilla)
- Font Awesome (iconos)
- Google Fonts (Inter)

---

⚙️ Funcionalidades

✔ Diseño moderno y responsive  
✔ Modo claro / oscuro con persistencia (localStorage)  
✔ Scroll suave entre secciones  
✔ Animaciones al hacer scroll (IntersectionObserver)  
✔ Navbar dinámica (sección activa)  
✔ Cards interactivas con hover  
✔ Videos embebidos (YouTube)  
✔ Botones personalizados para acceso a código  

---

🎨 UI / UX

Se aplicaron mejoras visuales enfocadas en:

- Jerarquía de información clara
- Separación de bloques (cards)
- Listas con iconos tipo check ✔
- Botones consistentes (CTA)
- Paleta profesional (claro y dark mode)
- Optimización para lectura rápida (recruiters)

---

📂 Estructura del proyecto


portfolio-web/
│
├── index.html
├── css/
│ └── styles.css
├── js/
│ └── script.js
├── assets/
│ └── img/
│ └── perfil.jpg
│
└── README.md


---

🧠 Lógica JavaScript

El archivo `script.js` incluye:

- Scroll suave para navegación interna
- Observer para animaciones (fade-in)
- Detección de sección activa en navbar
- Toggle de modo oscuro con guardado en localStorage

---

🌙 Modo oscuro

El sitio soporta dark mode mediante variables CSS:

```css
:root { ... }
.dark-mode { ... }
