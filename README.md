# 🛸 Rick and Morty · Explorador de Personajes

Aplicación web construida con **Astro** y **Tailwind CSS v4** que permite explorar el
multiverso de Rick and Morty consumiendo la [Rick and Morty API](https://rickandmortyapi.com/).

## ✨ Características

- 🔍 **Búsqueda en tiempo real** por nombre y especie (con _debounce_).
- 🎚️ **Filtros** por estado (vivo / muerto / desconocido) y género.
- 🪟 **Modal de detalle** con origen, ubicación, género y número de apariciones.
- ⏳ **Estados de carga** con _skeletons_ animados.
- 🚫 **Manejo de errores** y estado vacío con mensajes claros.
- 📄 **Paginación** completa con indicador de página.
- 🎨 **Diseño temático "portal"** con efectos de cristal, glow y fondo estelar.
- ♿ **Accesible** (navegación por teclado, `aria-*`, `prefers-reduced-motion`).
- 📱 **Totalmente responsive**.

## 🚀 Stack

- [Astro](https://astro.build) `^5`
- [Tailwind CSS](https://tailwindcss.com) `^4`
- [Rick and Morty API](https://rickandmortyapi.com/)

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando           | Acción                                              |
| :---------------- | :-------------------------------------------------- |
| `npm install`     | Instala las dependencias                            |
| `npm run dev`     | Inicia el servidor de desarrollo en `localhost:4321`|
| `npm run build`   | Compila el sitio de producción en `./dist/`         |
| `npm run preview` | Previsualiza la build localmente antes de desplegar |

## 📁 Estructura

```text
/
├── public/
│   └── favicon.svg          # Favicon temático (portal)
├── src/
│   ├── layouts/
│   │   └── Layout.astro      # HTML base, SEO y fuentes
│   ├── pages/
│   │   ├── index.astro       # Página principal
│   │   └── characters.astro  # UI + lógica del explorador
│   └── styles/
│       └── global.css        # Tema, animaciones y componentes
└── package.json
```

## 📜 Licencia

Proyecto educativo. Datos e imágenes provistos por la Rick and Morty API.
