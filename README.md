# 📝 Blog Post SENA - Proyecto de Diseño Web

## 👥 Información del Proyecto

**Institución:** SENA (Servicio Nacional de Aprendizaje)  
**Programa:** Análisis y Desarrollo de Software  
**Actividad:** Maquetación de la Interfaz gráfica en HTML GA5-220501095-AA1-EV04
**Fecha:** Junio 2025  

### 🧑‍💻 Equipo de Desarrollo
- **Ana Maria Monsalve** - Desarrolladora Principal
- **Juan Camilo González** - Co-desarrollador

---

## 📖 Descripción del Proyecto

Este proyecto consiste en el desarrollo de un **blog responsivo sobre diseño web y móvil**, implementado con tecnologías web modernas y frameworks actuales. El sitio web presenta contenido educativo sobre usabilidad, accesibilidad y mejores prácticas en el desarrollo de aplicaciones digitales.

### 🎯 Objetivos Académicos

- Implementar **HTML5 semántico** con estructura accesible
- Aplicar **CSS3 avanzado** con diseño responsivo
- Integrar **frameworks modernos** (Materialize CSS)
- Desarrollar **formularios funcionales** con validación
- Demostrar **buenas prácticas** de desarrollo web

---

## 🛠️ Tecnologías Utilizadas

### Frontend Core
- **HTML5** - Estructura semántica y accesible
- **CSS3** - Estilos avanzados y responsive design
- **JavaScript ES6+** - Interactividad y validación

### Frameworks y Librerías
- **Materialize CSS 1.0.0** - Framework Material Design
- **Material Icons** - Iconografía vectorial de Google
- **Google Fonts (Inter)** - Tipografía web optimizada

### Herramientas de Desarrollo
- **Git** - Control de versiones
- **VS Code** - Editor de código
- **GitHub** - Repositorio remoto

---

## 📁 Estructura del Proyecto

```
blog-post-sena/
├── 📄 index.html          # Página principal del blog
├── 📄 create.html         # Formulario de creación de posts
├── 📁 css/
│   ├── 🎨 style.css       # Estilos para la página principal
│   └── 🎨 create.css      # Estilos para el formulario
├── 📁 js/
│   ├── 📜 main.js         # Scripts de la página principal
│   └── 📜 create.js       # Scripts del formulario
├── 📚 README.md           # Documentación del proyecto
└── 🔧 .git/              # Control de versiones
```

---

## 🚀 Funcionalidades Implementadas

### 📰 Página Principal (index.html)
- **Navegación responsive** con enlaces funcionales
- **Hero section** con contenido destacado
- **Artículo educativo** sobre diseño web y móvil
- **Diseño adaptativo** para diferentes dispositivos
- **Integración de Materialize CSS** para componentes modernos

### 📝 Formulario de Creación (create.html)
- **Formulario funcional** para crear blog posts
- **Validación de campos** obligatorios
- **Barra de herramientas** de formato de texto
- **Diseño Material Design** con efectos visuales
- **Responsive design** optimizado para móviles

### 🎨 Características de Diseño
- **Color scheme** moderno y profesional
- **Tipografía Inter** para mejor legibilidad
- **Efectos de hover** y transiciones suaves
- **Box shadows** y border-radius para profundidad
- **Grid system** flexible y responsivo

---

## 💻 Instalación y Uso

### Requisitos Previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para CDNs)

### Instrucciones de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/usuario/blog-post-sena.git
cd blog-post-sena
```

2. **Abrir en el navegador**
```bash
# Método 1: Abrir directamente
open index.html

# Método 2: Servidor local (recomendado)
python -m http.server 8000
# Luego abrir: http://localhost:8000
```

### 🔗 Navegación del Sitio
- **BLOG** → Página principal con artículo
- **PUBLICA TU BLOG** → Formulario de creación
- **CONTACT** → Placeholder para futura implementación

---

## 🎨 Decisiones de Diseño

### Paleta de Colores
- **Primario:** `#2563eb` (Azul profesional)
- **Secundario:** `#667eea` (Azul degradado)
- **Fondo:** `#ffffff` (Blanco limpio)
- **Texto:** `#333333` (Gris oscuro)
- **Acento:** `#C8A8E9` (Lila suave)

### Tipografía
- **Familia:** Inter (Google Fonts)
- **Pesos:** 400 (Regular), 500 (Medium), 700 (Bold)
- **Justificación:** Excelente legibilidad en pantallas digitales

### Layout y Responsive
- **Breakpoints:** 600px (móvil), 992px (tablet), 1200px+ (desktop)
- **Grid system:** Flexbox + Materialize Grid
- **Metodología:** Mobile-first design

---

## 🔧 Características Técnicas

### HTML Semántico
```html
<!-- Ejemplo de estructura semántica -->
<main class="blog-main">
  <section class="blog-hero">
    <header>
      <h1>Título Principal</h1>
    </header>
  </section>
</main>
```

### CSS Modular
```css
/* Metodología BEM para nombres de clases */
.blog-header__nav
.blog-content__title
.form-container__input
```

### JavaScript Funcional
```javascript
// Validación de formularios
document.getElementById('contactForm').addEventListener('submit', validateForm);
```

---

## 📱 Compatibilidad

### Navegadores Soportados
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

### Dispositivos Testados
- 📱 **Móviles:** iPhone, Android (320px - 768px)
- 📱 **Tablets:** iPad, Android tablets (768px - 1024px)
- 💻 **Desktop:** Laptops y monitores (1024px+)

---

## 🧪 Validaciones y Testing

### Validación HTML
- ✅ **W3C HTML Validator** - Estructura semántica correcta
- ✅ **Accessibility checks** - WCAG 2.1 guidelines
- ✅ **SEO validation** - Meta tags y estructura

### Validación CSS
- ✅ **W3C CSS Validator** - Sintaxis correcta
- ✅ **Cross-browser testing** - Compatibilidad
- ✅ **Responsive testing** - Múltiples dispositivos

### Performance
- ✅ **Lighthouse Score** - Optimización web
- ✅ **PageSpeed Insights** - Velocidad de carga
- ✅ **Mobile-friendly test** - Google Mobile Test

---

## 📚 Conceptos Académicos Aplicados

### Principios de Diseño UX/UI
- **Usabilidad:** Interfaz intuitiva y fácil de usar
- **Accesibilidad:** Diseño inclusivo para todos los usuarios
- **Jerarquía visual:** Organización clara del contenido
- **Consistencia:** Patrones de diseño unificados

### Tecnologías Web Modernas
- **HTML5 Semántico:** Mejor SEO y accesibilidad
- **CSS3 Avanzado:** Flexbox, Grid, animaciones
- **JavaScript ES6+:** Programación moderna
- **Frameworks CSS:** Aceleración del desarrollo

### Metodologías de Desarrollo
- **Mobile-first:** Diseño pensado para móviles primero
- **Progressive Enhancement:** Mejora progresiva
- **Clean Code:** Código limpio y mantenible
- **Version Control:** Git para seguimiento de cambios

---

## 🏆 Logros del Proyecto

### Técnicos
- ✅ **Diseño 100% responsivo** en todos los dispositivos
- ✅ **Integración exitosa** de Materialize CSS
- ✅ **Código bien documentado** con comentarios explicativos
- ✅ **Formulario funcional** con validación JavaScript
- ✅ **Performance optimizada** con CDNs

### Académicos
- ✅ **Aplicación de conceptos** de diseño web modernos
- ✅ **Implementación de buenas prácticas** de desarrollo
- ✅ **Trabajo colaborativo** efectivo en equipo
- ✅ **Documentación completa** del proceso de desarrollo

---

## 📞 Contacto y Soporte

### Desarrolladores
- **Ana Maria Monsalve** - ana_mmonsalveb@soy.sena.edu.co
- **Juan Camilo González** - juan_cgonzalez26@soy.sena.edu.co

### Recursos Académicos
- **Plataforma SENA:** [Zajuna](https://zajuna.sena.edu.co/)
- **Actividad Original:** Maquetación de la Interfaz gráfica en HTML GA5-220501095-AA1-EV04

---

## 📄 Licencia

Este proyecto fue desarrollado con fines **educativos** para el SENA. 

**© 2025 - Proyecto Académico SENA - Análisis y Desarrollo de Software**

---

*Desarrollado con ❤️ por estudiantes del SENA - Comprometidos con la excelencia en el desarrollo web*