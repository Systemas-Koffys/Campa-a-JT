# ⚡ QUICK START - Inicia en 5 minutos

## 🎯 Resumen Ejecutivo

Tienes una **aplicación React profesional completa** lista para usar con:
- ✅ Sistema de login con dos roles (user/admin)
- ✅ CRUD completo de participantes y actividades
- ✅ Dashboard con estadísticas
- ✅ Generación de PDF (carnés)
- ✅ Importación de Excel
- ✅ Almacenamiento local (sin servidor)
- ✅ Diseño responsive y moderno
- ✅ Colores corporativos integrados

---

## 🚀 Instalación (3 pasos)

### 1️⃣ Descargar e instalar Node.js
```
👉 https://nodejs.org/
   Descargar versión LTS
```

### 2️⃣ En terminal (copiar y pegar)
```bash
cd campaign-district-6
npm install
npm start
```

### 3️⃣ Listo! 
Abre http://localhost:3000

---

## 🔑 Credenciales

| Usuario | Contraseña | Nivel |
|---------|-----------|--------|
| `user` | `123` | Lectura |
| `admin` | `password` | Control total |

---

## 📊 Primeros pasos

1. **Accede como admin**
2. **Administración → Importar**
3. Selecciona `Lista_Asistencia_D6_Final.xlsx`
4. ¡Listo! 120 participantes + 29 actividades cargadas

---

## 📁 Estructura de carpetas

```
campaign-district-6/
├── components/          ← Componentes React
│   ├── LoginPage.jsx    ← Página de login
│   ├── Dashboard.jsx    ← Estadísticas
│   ├── PeopleList.jsx   ← Listado de participantes
│   ├── PersonProfile.jsx ← Perfil individual + PDF
│   ├── AdminPanel.jsx   ← CRUD completo
│   └── InfoPage.jsx     ← Información + enlaces
├── utils/
│   └── DataManager.js   ← Gestión de datos
├── index.html           ← HTML principal
├── CampaignApp.jsx      ← App principal
├── package.json         ← Dependencias
└── README.md            ← Documentación completa
```

---

## 🔧 Funcionalidades principales

### 👤 Usuario Regular
- Ver dashboard
- Buscar participantes
- Ver perfil individual
- Descargar carnet en PDF

### 👨‍💻 Admin
- Todo lo anterior, más:
- **Crear** nuevos participantes
- **Editar** participantes (nombre, teléfono, fotos)
- **Eliminar** participantes
- **Crear** actividades
- **Editar** actividades
- Subir 2 fotos por persona
- Agregar enlaces de redes sociales

---

## 📤 Subir a GitHub

```bash
# Crear repositorio en GitHub primero

git init
git add .
git commit -m "Primera versión"
git remote add origin https://github.com/tu-usuario/campaign-district-6.git
git push -u origin main

# Para GitHub Pages:
npm run build
npm run deploy
```

---

## 🎨 Personalizar

### Colores corporativos
En `tailwind.config.js`:
```javascript
'campaign-green': '#0B5C3B',  // Verde oscuro
'campaign-red': '#E30613',    // Rojo
'campaign-pink': '#E8316E',   // Rosa
```

### Cambiar credenciales
En `components/LoginPage.jsx`:
```javascript
{ username: 'tu-usuario', password: 'tu-contraseña', role: 'user' }
```

### Agregar enlaces externos
En `components/InfoPage.jsx`:
```javascript
url: 'https://tu-dropbox-link'
url: 'https://tu-facebook'
url: 'https://tu-tiktok'
```

---

## 📱 Notas Importantes

✅ **Datos offline**: Todo se guarda en el navegador  
✅ **Sin servidor**: No necesita backend  
✅ **Responsivo**: Funciona en móvil, tablet, desktop  
✅ **Imprimible**: PDFs de alta calidad  

---

## ⚠️ Solución de problemas

### No aparece nada
- Abre DevTools (F12)
- Revisa la consola (Console)
- Recarga (Ctrl+R)

### Excel no importa
- Verifica que sea .xlsx
- No debe tener filtros aplicados
- Archivo original sin cambios

### Quiero cambiar las fotos de los logos
En `components/LoginPage.jsx`, `CampaignApp.jsx`, etc. busca:
```javascript
img src="https://i.postimg.cc/VvQp16sf/L-COLOR.png"
```

---

## 📞 Contacto & Soporte

**Desarrollado por**: Sistemas Koffy's  
**Versión**: 1.0.0  
**Última actualización**: Marzo 2026

Para problemas técnicos, revisar:
- `INSTALLATION.md` (más detallado)
- `README.md` (documentación completa)

---

## 📊 Datos Importados

- **120 participantes** del Distrito 6
- **29 actividades** registradas
- **Fechas**: Enero a Marzo 2026
- **Asistencias calculadas**: Automáticas

---

## 🎉 ¡Listo para presentar!

Tu aplicación está lista para:
- ✅ Mostrar a tu equipo
- ✅ Compartir en GitHub
- ✅ Publicar en la web
- ✅ Usar en cualquier dispositivo

---

**Cualquier duda, revisa los archivos .md o la consola del navegador (F12)**
