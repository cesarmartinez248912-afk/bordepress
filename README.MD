# BordaXpress - Despliegue en Vercel

## Estructura del proyecto

```
bordepress/
├── index.html      ← Página principal
├── vercel.json     ← Configuración de Vercel
└── README.md
```

## Opciones para desplegar en Vercel

---

### Opción 1: Sin código — Drag & Drop (más fácil)

1. Ve a [vercel.com](https://vercel.com) e inicia sesión (o crea una cuenta gratis)
2. En el dashboard, haz clic en **"Add New… → Project"**
3. Elige **"Upload"** o arrastra toda la carpeta `bordepress/`
4. Vercel detectará automáticamente que es un sitio estático
5. Haz clic en **"Deploy"**
6. ¡Listo! Obtendrás una URL tipo `bordepress.vercel.app`

---

### Opción 2: Con Vercel CLI

```bash
# 1. Instalar Vercel CLI
npm install -g vercel

# 2. Entrar a la carpeta del proyecto
cd bordepress

# 3. Desplegar
vercel

# Sigue las instrucciones en consola:
# - Set up and deploy? → Y
# - Which scope? → tu usuario
# - Link to existing project? → N
# - Project name? → bordepress (o el que prefieras)
# - In which directory is your code? → ./
# - Override settings? → N
```

---

### Opción 3: Con GitHub (recomendado para actualizaciones continuas)

1. Sube la carpeta `bordepress/` a un repositorio en GitHub
2. En Vercel → **"Add New → Project"**
3. Conecta tu cuenta de GitHub y selecciona el repositorio
4. Vercel detectará el sitio estático automáticamente
5. Cada `git push` al branch `main` desplegará automáticamente

---

## Dominio personalizado (opcional)

Una vez desplegado:
1. Ve a tu proyecto en Vercel → **Settings → Domains**
2. Agrega tu dominio (ej: `bordaxpress.com`)
3. Apunta tu DNS al dominio de Vercel según las instrucciones

---

> ✅ El sitio usa solo un archivo HTML con CDN externas (Tailwind, Google Fonts),
> por lo que no necesita configuración de build adicional.