# 🚀 Guía de Publicación en GitHub

## Paso 1: Crear el Repositorio en GitHub

1. Ve a [GitHub](https://github.com)
2. Haz clic en el botón "+" (esquina superior derecha)
3. Selecciona "New repository"
4. Configura:
   - **Nombre**: `laliga-checklist` (o el que prefieras)
   - **Descripción**: "Checklist de cromos LaLiga 2025-26 con gestión de repes y estadísticas"
   - **Visibilidad**: Public (o Private si prefieres que sea privado)
   - **NO** marques "Initialize with a README" (ya tenemos uno)
5. Haz clic en "Create repository"

## Paso 2: Subir los Archivos

Desde la terminal en tu proyecto:

```bash
# Inicializar Git (si no lo está)
git init

# Añadir el remote de GitHub
git remote add origin https://github.com/TU-USUARIO/laliga-checklist.git

# Añadir todos los archivos (excepto .gitignore)
git add .
git add -f .gitignore

# Crear el commit inicial
git commit -m "Initial commit: LaLiga 2025-26 Checklist"

# Subir a GitHub
git branch -M main
git push -u origin main
```

## Paso 3: Publicar en GitHub Pages (Opcional)

1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. En el menú lateral, busca **Pages**
4. En "Source", selecciona **main** como branch
5. Deja "/ (root)" como carpeta
6. Haz clic en **Save**
7. Tu sitio estará disponible en: `https://TU-USUARIO.github.io/laliga-checklist/html/checklist_cromos_laliga.html`

## Estructura Final Recomendada

```
laliga-checklist/
├── index.html                          # Página de inicio
├── html/
│   ├── checklist_cromos_laliga.html   # Página principal
│   ├── repes_cromos_laliga.html       # Gestión de repes
│   └── estadisticas_cromos_laliga.html # Estadísticas
├── logos/                              # Logos de equipos
├── cromos_data.json                    # Dataset
├── .gitignore                          # Ignora progreso personal
├── README.md                           # Documentación
└── GITHUB_SETUP.md                     # Esta guía
```

## ⚠️ Notas Importantes

### .gitignore
El archivo `.gitignore` está configurado para **NO subir**:
- `progreso_cromos_laliga.json` (tu progreso personal)

Esto significa que:
- ✅ El código base se subirá
- ❌ Tu progreso personal NO se subirá
- ✅ Cada usuario que descargue el proyecto tendrá su propio progreso

### Qué se Sube a GitHub

✅ **SÍ se sube**:
- Todos los HTML
- Todos los logos
- El dataset `cromos_data.json`
- README y documentación

❌ **NO se sube**:
- Tu progreso personal (`progreso_cromos_laliga.json`)

## 📝 Comandos Git Útiles

```bash
# Ver estado de los archivos
git status

# Ver cambios detallados
git diff

# Crear un commit con mensaje
git commit -m "Descripción del cambio"

# Subir cambios a GitHub
git push

# Descargar cambios de GitHub
git pull

# Ver el historial de commits
git log
```

## 🔄 Actualizar el Repositorio

Cuando hagas cambios:

```bash
# Ver qué archivos han cambiado
git status

# Añadir todos los cambios
git add .

# Crear un commit con descripción
git commit -m "Descripción de los cambios realizados"

# Subir a GitHub
git push
```

## 🌐 Enlaces Útiles

- **Repositorio**: `https://github.com/TU-USUARIO/laliga-checklist`
- **Demo en vivo** (si usas GitHub Pages): `https://TU-USUARIO.github.io/laliga-checklist/html/checklist_cromos_laliga.html`
- **Issues**: Para reportar errores o sugerencias
- **Releases**: Para versiones del proyecto

## ✨ Próximos Pasos

Una vez publicado:
1. Comparte el enlace con amigos que también coleccionen cromos
2. Acepta contribuciones si alguien quiere mejorar el proyecto
3. Mantén el proyecto actualizado con nuevos cromos si los hay
4. Considera añadir GitHub Actions para automatizar tareas

---

**¡Tu checklist de cromos está listo para ser compartido con el mundo! 🌍⚽**

