# Catálogo de Libros - EDUNLU 📚

Este proyecto es una aplicación web moderna diseñada para explorar y filtrar el catálogo de libros de la **Editorial de la Universidad Nacional de Luján (EDUNLU)**.

## 🚀 Características Principales

- **Búsqueda Dinámica**: Encuentra libros rápidamente por título o autor mediante un sistema de búsqueda en tiempo real.
- **Filtros Avanzados**:
  - Filtro por **Colecciones** (Ciencias, Sociedad en Movimiento, Aulas Universitarias, etc.).
  - Filtro por **Temas/Categorías**.
- **Ordenamiento Flexible**: Organiza el catálogo alfabéticamente (A-Z) o por fecha de publicación.
- **Interfaz Premium**: Diseño responsivo y fluido utilizando Tailwind CSS 4, con micro-animaciones y efectos hover para una mejor experiencia de usuario.
- **Acceso Directo**: Cada libro incluye un enlace directo para "Ver" más detalles o adquirirlo.

## 🛠️ Tecnologías

Este proyecto está construido con:

- [Astro 5](https://astro.build/) - Framework web para islas de interactividad.
- [Tailwind CSS 4](https://tailwindcss.com/) - Para estilos modernos y eficientes.
- [TypeScript](https://www.typescriptlang.org/) - Para un desarrollo más seguro y robusto.

## 📂 Estructura del Proyecto

```text
/
├── public/             # Recursos estáticos (favicon, etc.)
├── src/
│   ├── assets/         # Imágenes de portadas y otros medios
│   ├── components/     # Componentes Astro (Header, Catalogo, Footer)
│   ├── data/           # Datos del catálogo (products.ts)
│   ├── layouts/        # Estructura base de las páginas
│   ├── pages/          # Rutas del sitio (index.astro)
│   └── styles/         # CSS Global
└── package.json        # Dependencias y scripts
```

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando           | Acción                                           |
| :---------------- | :----------------------------------------------- |
| `npm install`     | Instala las dependencias                         |
| `npm run dev`     | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`   | Compila el sitio para producción en `./dist/`    |
| `npm run preview` | Previsualiza la versión compilada localmente     |
| `npm run astro`   | Ejecuta comandos de la CLI de Astro              |

---
Desarrollado para la **Universidad Nacional de Luján**.
