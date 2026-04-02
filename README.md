# 🚌 TransLog — Sistema de Gestión de Transporte Corporativo

> Demo interactivo completo · Sin backend · Sin instalación

[![Deploy to GitHub Pages](https://img.shields.io/badge/Demo-Live-00e5b3?style=for-the-badge)](https://YOUR_USERNAME.github.io/translog)

---

## 🚀 Ver demo en vivo

👉 **[YOUR_USERNAME.github.io/translog](https://YOUR_USERNAME.github.io/translog)**

---

## 📋 Funcionalidades del Demo

| Pantalla | Descripción |
|---|---|
| 📊 **Dashboard** | KPIs, gráfica por ruta, ranking, comparativa sucursales |
| 🗺️ **Viajes** | Historial con costo/persona, formulario para crear viajes |
| 📷 **Check-in** | Simulación OCR con confidence scores + formulario QR |
| 📋 **Reportes** | Tabla de costo por persona, filtros, exportar Excel |

---

## 💻 Correr localmente

**Sin instalar nada:**
```
Abre index.html directamente en tu navegador
```

**Con un servidor local (opcional):**
```bash
# Python 3
python -m http.server 8080

# Node
npx serve .
```

Luego abre `http://localhost:8080`

---

## 📁 Estructura

```
translog/
├── index.html          ← App completa (React via CDN, sin build)
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml  ← Auto-deploy a GitHub Pages
```

---

## 🏗️ Stack del Prototipo

- **React 18** via CDN (sin npm, sin build step)
- **Datos mock** incluidos en el HTML
- **Zero dependencias** locales

## 🏗️ Stack de Producción (Backend Real)

Ver carpeta `/docs/architecture.md` para el stack completo:
- Next.js 14 + Supabase + Prisma
- Google Vision API (OCR)
- Vercel deployment

---

## 🌐 Deploy en GitHub Pages

Se despliega automáticamente con cada push a `main` vía GitHub Actions.

Ver `.github/workflows/deploy.yml`

---

## 📄 Licencia

MIT — Libre para uso y modificación
