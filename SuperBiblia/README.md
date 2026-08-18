# 🚀 Guía: Cómo Subir tu App a GitHub y Vercel (Paso a Paso)

¡Felicidades! Tu aplicación **Súper Biblia Explorer** está lista para ser publicada en internet de forma **100% gratuita** con un enlace público (ejemplo: `https://super-biblia-explorer.vercel.app`) para que cualquier persona en PC o smartphone pueda usarla y compartir versículos.

---

## 📁 Archivos de tu Proyecto
Para subir tu app, solo necesitas estos dos archivos que ya están listos en tu carpeta:
1. `index.html` (La aplicación completa interactiva)
2. `vercel.json` (Configuración de publicación para Vercel)

---

## 🟢 PASO 1: Subir tu Código a GitHub (Elige Opción A o B)

### Opción A: Desde la Página Web de GitHub (¡La más fácil sin comandos!)
1. Ve a [github.com](https://github.com/) e inicia sesión (o crea tu cuenta gratuita).
2. Haz clic en el botón verde **"New"** (Nuevo Repositorio) arriba a la izquierda.
3. En **Repository name**, escribe: `super-biblia-explorer`
4. Asegúrate de marcarlo como **Public** y presiona el botón verde **"Create repository"**.
5. En la pantalla que aparece, haz clic en el enlace azul **"uploading an existing file"** (subir un archivo existente).
6. Arrastra y suelta los archivos `index.html` y `vercel.json` en la ventana.
7. Haz clic abajo en el botón verde **"Commit changes"**. ¡Listo, ya está en GitHub!

---

### Opción B: Usando la Terminal / Git
Si tienes Git instalado en tu computadora:
```bash
git init
git add .
git commit -m "Primer lanzamiento de Super Biblia Explorer"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/super-biblia-explorer.git
git push -u origin main
```

---

## ⚡ PASO 2: Publicar Gratis en Vercel (En 30 Segundos)

1. Entra en [vercel.com](https://vercel.com/) y haz clic en **Sign Up** o **Log In** seleccionando **"Continue with GitHub"**.
2. Una vez dentro de tu panel de Vercel, haz clic en el botón **"Add New..."** ➔ **"Project"**.
3. Verás una lista con tus repositorios de GitHub. Busca `super-biblia-explorer` y haz clic en el botón azul **"Import"**.
4. En la configuración del proyecto:
   - **Framework Preset**: Déjalo en `Other`
   - **Root Directory**: `./` (o déjalo por defecto)
5. Haz clic en el botón azul **"Deploy"**.
6. ¡En unos 15 segundos verás una lluvia de confeti 🎉 y tu enlace público generado! (ej: `https://super-biblia-explorer.vercel.app`).

---

## 📲 PASO 3: Compartir con Amigos y Familiares
- Copia tu nuevo enlace de Vercel (`https://tu-proyecto.vercel.app`).
- Pégalo en tus grupos de WhatsApp, redes sociales o envíalo a tus contactos.
- En teléfonos Android e iPhone, tus usuarios pueden abrirlo en Chrome o Safari y seleccionar **"Agregar a la pantalla principal"** para usarlo como una aplicación nativa instalada.
