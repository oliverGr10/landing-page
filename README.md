# MISTHEC — Landing Page

Landing page corporativa para **MISTHEC**, empresa de tecnología con sede en Arequipa, Perú.

## Stack

- [Astro](https://astro.build/) v6
- GSAP v3 (animaciones)
- CSS puro con variables (sin framework CSS)

## Requisitos

- Node.js 18+
- npm

## Instalación

```bash
npm install
```

## Comandos

| Comando | Descripción |
|---------|-------------|
| `npm run dev` | Servidor de desarrollo en `http://localhost:4321` |
| `npm run build` | Build de producción en `dist/` |
| `npm run preview` | Preview del build de producción |

## Estructura

```
src/
├── components/
│   ├── Navbar.astro
│   ├── Footer.astro
│   ├── Hero.astro
│   ├── Benefits.astro
│   ├── HowItWorks.astro
│   ├── ProductView.astro
│   ├── Testimonials.astro
│   └── Contact.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css

public/
└── images/        # Logo y fotos
```

## Deploy

El build genera archivos estáticos en `dist/` listos para subir a cualquier hosting (Netlify, Vercel, etc.).
