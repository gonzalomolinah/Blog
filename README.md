# blog · gonzalomolina.space

Sitio personal estático de Gonzalo Molina, basado en la plantilla **Solid State** de HTML5 UP y desplegado con GitHub Pages.

## Qué incluye

- Página principal (`index.html`) con proyectos destacados.
- Página de contacto (`contact.html`) + formulario vía FormSubmit.
- Álbum estático (`album.html`) y versión conectada a Supabase (`album_db.html`).
- Panel de administración (`admin.html`) para gestión de contenido/fotos.
- Página de agradecimiento (`gracias.html`) y error (`404.html`).

## Estructura actual

```txt
blog/
├── .github/
│   └── workflows/
├── assets/
│   ├── css/
│   └── js/
├── images/
├── 404.html
├── admin.html
├── album.html
├── album_db.html
├── contact.html
├── gracias.html
├── index.html
├── LICENSE.txt
└── README.md
```

## Uso local

```bash
git clone https://github.com/gonzalomolinah/blog.git
cd blog
# abrir index.html o usar Live Server
```

## Notas

- Se normalizaron rutas de imágenes/links para evitar dependencias innecesarias de `raw.githubusercontent.com`.
- Se agregaron metadatos básicos de SEO/performance en las páginas principales.

## Créditos

- Plantilla: [HTML5 UP - Solid State](https://html5up.net/solid-state)
- Íconos: Font Awesome

## Contacto

- Email: yo@gonzalomolina.space
- Instagram: @gonzalomolinah
