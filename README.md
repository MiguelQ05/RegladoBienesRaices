# Reglado Bienes Raíces

Este proyecto es una plataforma web premium para **Reglado Bienes Raíces**, una firma de consultoría técnica y gestión de activos inmobiliarios. La aplicación destaca por su diseño sofisticado, minimalista y de alto rendimiento, enfocado en transmitir profesionalidad y rigor técnico.

## 🚀 Tecnologías Utilizadas

- **Framework**: [Vue 3](https://vuejs.org/) (Composition API con `<script setup>`)
- **Herramienta de Construcción**: [Vite](https://vitejs.dev/)
- **Estilos**: Vanilla CSS (CSS puro) con variables modernas y sistema de diseño personalizado.
- **Animaciones**: CSS Nativo e Intersection Observer API para efectos de revelado al hacer scroll.

## 📂 Estructura del Proyecto

La estructura del código sigue una organización modular y limpia:

```text
reglado-bienes-raices/
├── public/              # Activos estáticos públicos (favicons, etc.)
├── src/
│   ├── assets/          # Estilos globales y tokens de diseño
│   │   └── main.css     # Sistema de diseño, variables y utilidades base
│   ├── components/      # Componentes de UI reutilizables
│   │   ├── Navbar.vue   # Navegación interactiva con efectos de scroll
│   │   ├── HeroSection.vue # Sección de impacto inicial (Hero)
│   │   └── Footer.vue   # Pie de página estructurado y premium
│   ├── views/           # Vistas principales (páginas)
│   │   ├── LandingPage.vue # Página principal que integra todas las secciones
│   │   └── LegalNotice.vue # Página dedicada al Aviso Legal
│   ├── App.vue          # Componente raíz (gestiona el enrutamiento por hash y efectos globales)
│   └── main.js          # Punto de entrada de la aplicación
├── index.html           # Plantilla HTML base
├── package.json         # Dependencias y scripts del proyecto
└── vite.config.js       # Configuración de Vite
```

## 🧩 Componentes y Vistas

### 🌍 Vistas Principales

1.  **LandingPage.vue**: Es el núcleo de la web. Organiza la narrativa de la marca a través de secciones interactivas:
    - **HeroSection**: Presentación visual de alto impacto.
    - **Qué Hacemos**: Detalle de los servicios (Intermediación, Análisis, Gestión).
    - **Sobre Nosotros**: Historia y marco operativo de la firma.
    - **Valores**: Pilares fundamentales (Neutralidad, Rigor Técnico, Estructura).
2.  **LegalNotice.vue**: Vista detallada que contiene toda la información legal exigida, manteniendo la coherencia estética del sitio.

### 🛠️ Componentes Clave

-   **Navbar.vue**: Una barra de navegación inteligente que cambia su apariencia según el scroll y permite la navegación por secciones y cambios de página instantáneos.
-   **HeroSection.vue**: Diseñado con un estilo de "revista premium", utiliza tipografía elegante y una composición asimétrica.
-   **Footer.vue**: Un pie de página robusto que organiza enlaces, información de contacto y branding en un entorno de modo oscuro refinado.

## ✨ ¿Qué presenta en la Web?

La web ofrece una experiencia de usuario fluida y visualmente impactante:

-   **Sistema de Revelado (Scroll Reveal)**: Los elementos aparecen suavemente con animaciones de "fade up" y dibujado de iconos SVG a medida que el usuario navega.
-   **Diseño Adaptativo (Responsive)**: Optimización total para dispositivos móviles, tablets y escritorio, ajustando fuentes y espaciados mediante tipografía fluida.
-   **Estética Premium**: Uso de una paleta de colores basada en tonalidades **Gold** (Dorado), **Ink** (Tinta) y **Stone** (Piedra), combinada con tipografías de alta calidad como *Cormorant Garamond* (para títulos) y *DM Sans* (para lectura).
-   **Interactividad**: Botón de "Volver Arriba" dinámico que cambia su color según el fondo (claro/oscuro) para mantener la visibilidad y elegancia.

## 🛠️ Instalación y Desarrollo

Para ejecutar este proyecto localmente, asegúrate de tener instalado [Node.js](https://nodejs.org/).

1. **Instalar dependencias**:
   ```bash
   npm install
   ```

2. **Ejecutar en modo desarrollo**:
   ```bash
   npm run dev
   ```

3. **Construir para producción**:
   ```bash
   npm run build
   ```

---
*Este proyecto refleja el compromiso de Reglado Bienes Raíces con la excelencia técnica y la transparencia en el sector inmobiliario.*
