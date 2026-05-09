# VendePro 🛍️

Plataforma de ventas directas con dos roles: **Vendedor** y **Promotor**.

## ✨ Funcionalidades

- 🔐 Registro e inicio de sesión por rol
- 🏪 **Vendedor**: gestiona catálogo, sube imágenes desde galería, edita precios
- 📣 **Promotor**: consulta catálogo, ve comisiones con gráficas
- 📷 Subida de imágenes desde galería (Android e iPhone) — JPG, PNG, WEBP
- 💬 Botón WhatsApp directo al número de ventas
- 📊 Gráficas de barras y dona en el dashboard
- 💾 Datos guardados en localStorage (sin backend requerido)
- 🌙 Dark mode completo

## 🚀 Deploy en Vercel

1. Sube esta carpeta a un repositorio de GitHub
2. Ve a [vercel.com](https://vercel.com) → New Project
3. Importa tu repositorio
4. Vercel detecta automáticamente el `vercel.json` → **Deploy**
5. En ~30 segundos tienes tu URL pública

## 📁 Estructura

```
/
├── index.html      ← App completa (todo en un archivo)
├── vercel.json     ← Configuración de deploy
└── README.md       ← Este archivo
```

## 📱 Número de WhatsApp configurado

El botón "Comprar por WhatsApp" está conectado al número **4481068542**.
Para cambiarlo, busca `4481068542` en `index.html` y reemplázalo.

## 🔧 Tecnologías

- HTML5 + CSS3 + JavaScript vanilla
- Chart.js 4.4 (gráficas)
- Google Fonts (Clash Display + Satoshi)
- localStorage para persistencia de datos
