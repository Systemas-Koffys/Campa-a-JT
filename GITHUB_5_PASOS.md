# 🚀 SUBIR A GITHUB EN 5 PASOS (KEVIN FLORES)

## ⚠️ PRIMERO: REVOCA EL TOKEN QUE COMPARTISTE

1. Ve a: https://github.com/settings/tokens
2. Busca el token que compartiste
3. Click "Delete"

## ✅ LUEGO: CREA UN TOKEN NUEVO

1. Ve a: https://github.com/settings/tokens
2. Click "Generate new token (classic)"
3. Dale permisos: `repo` y `workflow`
4. Click "Generate token"
5. **COPIA EL TOKEN** (lo necesitarás en el Paso 4)

---

## 📋 LOS 5 PASOS

### Paso 1: Descargar archivos
- Descarga TODOS los archivos
- Crea carpeta: `campaign-district-6`
- Coloca todos los archivos dentro

### Paso 2: Crear repositorio en GitHub
1. Ve a https://github.com/new
2. Nombre: `campaign-district-6`
3. Descripción: `Aplicación de gestión de campaña electoral - Distrito 6`
4. Visibility: **Public**
5. Click "Create repository"
6. **COPIA LA URL** que aparece (algo como: https://github.com/kevinflores/campaign-district-6.git)

### Paso 3: Abrir Terminal
- 🪟 Windows: Click derecho en la carpeta → "Abrir PowerShell aquí"
- 🍎 Mac: Terminal → `cd /ruta/a/campaign-district-6`
- 🐧 Linux: Terminal → `cd ~/ruta/a/campaign-district-6`

### Paso 4: Ejecutar estos comandos (uno por uno)

**Comando 1:**
```bash
git config --global user.name "Kevin Flores"
git config --global user.email "kevinflores@campaign-district6.com"
```

**Comando 2:**
```bash
git init
```

**Comando 3:**
```bash
git add .
```

**Comando 4:**
```bash
git commit -m "🚀 Campaign District 6 - Versión inicial"
```

**Comando 5:**
```bash
git remote add origin https://github.com/kevinflores/campaign-district-6.git
```
⚠️ Reemplaza `kevinflores` con tu usuario real

**Comando 6:**
```bash
git branch -M main
```

**Comando 7:**
```bash
git push -u origin main
```

Cuando te pida autenticación:
- **Username**: Tu usuario de GitHub
- **Password**: El TOKEN que copiaste

### Paso 5: Activar GitHub Pages

1. Ve a tu repositorio: https://github.com/kevinflores/campaign-district-6
2. Settings → Pages
3. Source: "Deploy from a branch"
4. Branch: "main"
5. Folder: "/ (root)"
6. Click "Save"

**Espera 2-3 minutos...**

Tu aplicación estará en:
```
https://kevinflores.github.io/campaign-district-6
```

---

## ✅ ¡LISTO!

- 🌐 URL pública: https://kevinflores.github.io/campaign-district-6
- 📂 Código en GitHub: https://github.com/kevinflores/campaign-district-6
- 👤 Usuario demo: user / 123
- 🔑 Admin: admin / password

---

**Si algo falla:** Lee `GITHUB_UPLOAD_MANUAL.txt` para la versión detallada
