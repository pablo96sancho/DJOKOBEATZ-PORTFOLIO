# 🎵 DJOKOBEATZ — Portfolio Web & Showcase

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg?style=for-the-badge)](LICENSE)

Bienvenido al repositorio oficial del **Portfolio Web de DJOKOBEATZ**, diseñado tanto como escaparate profesional para servicios de **producción musical, mezcla y masterización**, como proyecto demostrativo de **desarrollo frontend responsivo y moderno**.

---

## 🌟 Características Principales

- **Diseño Moderno & Glassmorphism:** Estética urbana premium cuidada al detalle con gradientes, sombras HSL y animaciones fluidas.
- **Modo Claro / Oscuro (Dark Mode):** Alternador dinámico que detecta la preferencia del sistema operativo y guarda la elección del usuario en `localStorage`.
- **Efectos Scroll Reveal & Stagger:** Animación progresiva de elementos mediante la API nativa `IntersectionObserver`.
- **Navegación Inteligente (ScrollSpy):** Menú de navegación que resalta automáticamente la sección activa en pantalla.
- **Menú Responsive (Hamburguesa):** Navegación adaptada a dispositivos móviles.
- **Reproductores de Audio/Vídeo Integrados:** Tarjetas interactivas con _iframes_ optimizados (`loading="lazy"`) para demostraciones de Beats y Colaboraciones.
- **Feedback de Contacto Interactivo:** Copiado de correo electrónico al portapapeles en un solo clic con respuesta visual dinámica sin alertas intrusivas.

---

## 🛠️ Tecnologías Utilizadas

- **Frontend:** HTML5 Semántico, CSS3 Moderno (Custom Properties/Variables, Flexbox, CSS Grid), Vanilla JavaScript (ES6+).
- **Tipografía:** Google Fonts (_Bebas Neue_, _Syne_, _DM Sans_).
- **Despliegue:** GitHub Pages + GitHub Actions CI/CD.

---

## 📂 Estructura del Repositorio

```text
PORTFOLIO/
├── Assets/                   # Recursos gráficos e imágenes optimizadas
│   ├── DJOKOBLACK.png
│   ├── DJOKOWHITE.png
│   ├── IMG_2616.PNG
│   ├── LOGO DJOKO 1.png
│   └── LOGO DJOKO 2.png
├── archive/                  # Borradores e historial de versiones
├── .github/workflows/
│   └── deploy.yml            # CI/CD Despliegue automático en GitHub Pages
├── index.html                # Estructura principal de la aplicación web
├── style.css                 # Sistema de diseño, variables y temas
├── CARTA_PRESENTACION.md     # Carta de presentación profesional para empresas
├── GUIA_GITHUB.md            # Instrucciones paso a paso para subir a GitHub
├── LICENSE                   # Licencia de código abierto MIT
└── README.md                 # Documentación del proyecto
```

---

## 🚀 Cómo Ejecutar Localmente

No requiere instalación de dependencias ni servidores complejos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Pablo96sancho/PORTFOLIO.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd PORTFOLIO
   ```
3. Abre `index.html` en tu navegador o utiliza extensiones como **Live Server** en VS Code.

---

## 🌐 Publicación en GitHub Pages

Este proyecto incluye un flujo de trabajo automático con **GitHub Actions** (`.github/workflows/deploy.yml`).

Para publicar tu web gratis en GitHub Pages:

1. Sube los cambios a la rama `main` en tu repositorio de GitHub.
2. Ve a **Settings > Pages** en tu repositorio de GitHub.
3. En **Source**, selecciona **GitHub Actions**.
4. ¡Tu sitio estará disponible públicamente en `https://Pablo96sancho.github.io/PORTFOLIO/`!

_(Consulta la [GUIA_GITHUB.md](GUIA_GITHUB.md) para ver los comandos detallados)._

---

## 📧 Contacto & Redes

- **Email:** `pablo96sancho@gmail.com`
- **Instagram:** [@djokobeatz](https://www.instagram.com/djokobeatz/)
- **YouTube:** [DJOKOBEATZ Channel](https://www.youtube.com/@DJOKOBEATZ/featured)
- **Beatstars:** [djokobeatz](https://www.beatstars.com/djokobeatz)

---

_Desarrollado con ❤️ por Pablo Sancho._
