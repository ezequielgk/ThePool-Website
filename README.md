#  ThePool Portfolio Website

## 📋 Descripción

Sitio web moderno y responsive ThePool Graphic Designer Made by [Arsbyte](https://github.com/Ars-byte) [Ezequiel](https://github.com/ezequielgk) , construido con tecnologías web estáticas. Incluye documentación completa, preguntas frecuentes, información del equipo y recursos para la comunidad.

## 🛠️ Tecnologías utilizadas

- **Frontend**: HTML5, CSS3, JavaScript ES6+

## 📁 Estructura del proyecto

```

/
├── assets/
│   ├── fonts/              # Tipografías locales
│   ├── img/
│   │   ├── avatars/        # Agrupación lógica
│   │   │   ├── arsbyte.png
│   │   │   └── ezequiel.png
│   │   └── gallery/        # Nombres descriptivos en lugar de hashes
│   │       ├── hero-bg.png
│   │       └── feature-1.png
│   └── svg/                # Iconos vectoriales
├── css/
│   ├── modules/            # Componentes específicos
│   │   ├── nav.css
│   │   ├── footer.css
│   │   └── slider.css
│   ├── state/              # Cambios de estado
│   │   ├── responsive.css
│   │   └── animations.css
│   ├── base.css            # Reset y tipografía
│   ├── variables.css       # Design Tokens (colores, spacing)
│   └── main.css            # Archivo raíz que importa el resto
├── js/                     # Minúscula para consistencia
│   ├── components/         # Lógica de UI
│   │   ├── slider.js
│   │   └── progress.js
│   ├── core/               # Lógica de datos/config
│   │   ├── config.js
│   │   └── events.js
│   ├── utils/              # Funciones de ayuda
│   │   └── dom-tools.js
│   └── main.js             # Punto de entrada (antes app.js)
└── index.html
```

## Instalación y desarrollo

### Prerrequisitos

- **Navegador web moderno** (Chrome, Firefox, Safari, Edge)
- **Servidor local** (recomendado para desarrollo)

### Desarrollo local

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/ezequielgk/ThePool-Website.git
   cd ThePool-Website
``

2. **Inicia un servidor local**
    
    **Opción 1: Python**
    
    ```bash
    python -m http.server 8000
    # O con Python 3
    python3 -m http.server 8000
    ```
    
    **Opción 3: VS Code Live Server**
    
    - Instala la extensión "Live Server"
    - Click derecho en `index.html` → "Open with Live Server"


:b
