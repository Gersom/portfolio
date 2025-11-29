# Portfolio Personal - Gersom Alaja

Portafolio personal de desarrollador Fullstack especializado en Frontend con React y Vue.js.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 🚀 Demo

Visita el portfolio en vivo: [Tu URL aquí cuando lo despliegues]

## ✨ Características

- **Diseño Moderno y Profesional**: Interfaz limpia con efectos glassmorphism
- **Totalmente Responsive**: Optimizado para dispositivos móviles, tablets y escritorio
- **Animaciones Fluidas**: Transiciones suaves y efectos de scroll
- **Cursor Personalizado**: Cursor interactivo que responde a elementos
- **Barra de Progreso**: Indicador visual del progreso de scroll
- **Navegación Suave**: Smooth scroll entre secciones
- **Performance Optimizado**: Carga rápida y eficiente

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos avanzados con animaciones
- **JavaScript Vanilla**: Interactividad sin dependencias
- **Tailwind CSS**: Framework CSS utility-first
- **IBM Plex Sans**: Tipografía profesional

## 📂 Estructura del Proyecto

```
portfolio/
│
├── index.html          # Estructura principal del sitio
├── styles.css          # Estilos personalizados y animaciones
├── main.js             # Lógica de interactividad
└── README.md           # Documentación del proyecto
```

## 🎨 Paleta de Colores

- **Primary**: `#0a0e27` - Azul oscuro profundo
- **Secondary**: `#1a1f3a` - Azul oscuro medio
- **Accent**: `#00d9ff` - Cyan brillante
- **Accent Warm**: `#7affa7` - Verde claro
- **Text**: `#e8eaed` - Blanco suave
- **Text Dim**: `#9ca3af` - Gris claro

## 🚀 Instalación y Uso

### Opción 1: Clonar el repositorio

```bash
# Clonar el repositorio
git clone https://github.com/Gersom/portfolio.git

# Navegar al directorio
cd portfolio

# Abrir index.html en tu navegador
# O usar un servidor local como Live Server en VS Code
```

### Opción 2: Descarga directa

1. Descarga los archivos del repositorio
2. Abre `index.html` en tu navegador
3. ¡Listo!

## 🌐 Despliegue en GitHub Pages

1. Sube los archivos a tu repositorio de GitHub
2. Ve a Settings > Pages
3. Selecciona la rama principal (main/master)
4. Guarda y espera unos minutos
5. Tu portfolio estará disponible en: `https://tu-usuario.github.io/portfolio`

## 📋 Secciones del Portfolio

- **Hero**: Presentación principal con nombre y título
- **Sobre mí**: Información personal y tech stack
- **Proyectos**: Proyectos destacados con enlaces
- **Experiencia**: Historial laboral con timeline
- **Educación**: Formación académica y certificaciones
- **Contacto**: Enlaces a redes sociales y email

## 🔧 Personalización

### Cambiar información personal

Edita `index.html` y busca las siguientes secciones:

```html
<!-- Hero Section -->
<h1>Tu Nombre</h1>
<h2>Tu Título</h2>

<!-- About Section -->
<p>Tu descripción</p>

<!-- Contact Section -->
<a href="mailto:tu-email@example.com">Email</a>
```

### Modificar colores

Edita `styles.css` y cambia las variables CSS:

```css
:root {
  --primary: #tu-color;
  --accent: #tu-color;
  /* ... más variables */
}
```

### Agregar proyectos

Duplica un bloque de proyecto en `index.html`:

```html
<div class="glass-card p-6 fade-in delay-1">
  <div class="mb-4">
    <span class="text-sm text-[var(--accent)]">Categoría</span>
    <h3 class="text-2xl font-bold mt-2 mb-3">Nombre del Proyecto</h3>
  </div>
  <p class="text-[var(--text-dim)] mb-4">
    Descripción del proyecto
  </p>
  <div class="flex flex-wrap gap-2 mb-4">
    <span class="tech-pill text-xs">Tecnología 1</span>
    <span class="tech-pill text-xs">Tecnología 2</span>
  </div>
  <a href="URL" target="_blank" class="project-link">Ver Proyecto →</a>
</div>
```

## 📱 Responsive Design

El portfolio está optimizado para:

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Características Destacadas

### Cursor Personalizado
```javascript
// El cursor cambia de tamaño al hacer hover sobre elementos interactivos
cursor.classList.add('expand');
```

### Barra de Progreso
```javascript
// Muestra el progreso de scroll en la página
const scrolled = (window.scrollY / windowHeight) * 100;
progressBar.style.width = scrolled + '%';
```

### Intersection Observer
```javascript
// Las animaciones se activan cuando los elementos entran en el viewport
observer.observe(element);
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Gersom Alaja**

- GitHub: [@Gersom](https://github.com/Gersom)
- LinkedIn: [gersomalaja](https://linkedin.com/in/gersomalaja)
- Email: gersomalaja@gmail.com

## 🙏 Agradecimientos

- Fuentes tipográficas por [Google Fonts](https://fonts.google.com/)
- Framework CSS por [Tailwind CSS](https://tailwindcss.com/)
- Iconos emoji nativos del sistema

---

⭐ Si te gustó este proyecto, dale una estrella en GitHub!

**Hecho con ❤️ por Gersom Alaja**
