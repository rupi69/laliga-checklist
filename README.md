# ⚽ LaLiga 2025-26 - Checklist de Cromos

Aplicación web completa para gestionar tu colección de cromos de LaLiga 2025-26. Marca tus cromos obtenidos, gestiona tus repes y consulta estadísticas detalladas.

![LaLiga](https://img.shields.io/badge/LaLiga-2025--26-red)
![HTML5](https://img.shields.io/badge/HTML5-100%25-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

## 📋 Características

### ✨ Checklist Principal
- ✅ **639 cromos** de LaLiga 2025-26 con 4 ediciones
- 🔍 **Filtros avanzados**: Equipo, Sección, Edición
- 🔎 **Búsqueda** por nombre de jugador
- 💾 **Guardado automático** en localStorage
- 📊 **Estadísticas en tiempo real**
- 🎨 **Diseño minimalista** y completamente responsive
- 🖼️ **Logos oficiales** de los 20 equipos

### 🔄 Gestión de Repes
- ⚽ Añadir repes por equipo (solo para Jugadores) y sección
- 📝 Lista compacta de NC (números de carta)
- 🎨 Colores personalizados por equipo/sección
- ✏️ Editar y eliminar repes fácilmente
- 💾 Guardado persistente

### 📊 Estadísticas Detalladas
- 📈 Estadísticas generales (Total, Obtenidos, %, Faltantes)
- 🏆 Estadísticas por equipos (20 equipos con logos)
- 📉 Estadísticas por secciones (6 secciones)
- 📊 Barras de progreso visuales

## 🚀 Instalación

### Método 1: Descargar y usar directamente

1. Descarga o clona el repositorio:
```bash
git clone https://github.com/tu-usuario/laliga-checklist.git
cd laliga-checklist
```

2. Abre `index.html` o `html/checklist_cromos_laliga.html` en tu navegador
3. ¡Empieza a marcar cromos!

### Método 2: Con servidor local (recomendado)

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/laliga-checklist.git
cd laliga-checklist
```

2. Inicia un servidor HTTP:
```bash
# Python 3
python -m http.server 8000

# O con Node.js
npx http-server
```

3. Abre en tu navegador: `http://localhost:8000/html/checklist_cromos_laliga.html`

## 📁 Estructura del Proyecto

```
laliga-checklist/
├── index.html                          # Página de inicio
├── html/
│   ├── checklist_cromos_laliga.html   # 📋 Aplicación principal
│   ├── repes_cromos_laliga.html       # 🔄 Gestión de repes
│   └── estadisticas_cromos_laliga.html # 📊 Estadísticas
├── logos/                              # 20 logos oficiales de equipos
├── cromos_data.json                    # Dataset de cromos (639 cromos)
├── .gitignore                          # Archivos ignorados por Git
└── README.md                           # Este archivo
```

## 📊 Datos

- **Total cromos**: 639
- **Equipos**: 20
- **Secciones**: 6
  - Jugadores
  - ADN LA LIGA / SUPERKIDS
  - Mister Cero
  - Mix
  - Últimos fichajes
  - Extra Gold
- **Ediciones**: 
  - 1ª Edición: 467 cromos
  - 2ª Edición: 60 cromos
  - 3ª Edición: 50 cromos
  - 4ª Edición: 62 cromos

## 🎯 Uso

### Página Principal (Checklist)
1. Abre `html/checklist_cromos_laliga.html` o usa el `index.html` como punto de entrada
2. Filtra por **Equipo**, **Sección** o **Edición**
3. Busca cromos por nombre
4. Haz clic en cada cromo para marcarlo como obtenido
5. Guarda tu progreso con el botón "Guardar Progreso"

### Gestión de Repes
1. Haz clic en "🔄 Gestionar Repes" desde la página principal
2. Selecciona un equipo (solo para Jugadores) y una sección
3. Introduce el NC (número de carta en el equipo)
4. Tus repes se guardan automáticamente

### Estadísticas
1. Haz clic en "📊 Ver Estadísticas"
2. Visualiza tu progreso general y por equipos/secciones
3. Los datos se actualizan automáticamente

## 💾 Guardado de Datos

- **Progreso**: Se guarda automáticamente en `localStorage` de tu navegador
- **Exportar**: Puedes descargar tu progreso como JSON desde "Guardar Progreso"
- **Repes**: Se guardan en `localStorage` y persisten entre sesiones

## 🛠️ Tecnologías

- HTML5
- CSS3
- JavaScript (Vanilla ES6+)
- localStorage API

## 📝 Notas

- **Sin base de datos**: Todo funciona en el navegador del cliente
- **Privacidad**: Tus datos nunca salen de tu navegador
- **Offline**: Funciona completamente sin conexión a internet
- **Responsive**: Funciona perfectamente en móvil, tableta y desktop

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o tienes una sugerencia:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## ⚡ Características Técnicas

- **Completamente offline**: No requiere servidor
- **Sin dependencias**: Solo HTML, CSS y JavaScript puro
- **Compatible**: Funciona en todos los navegadores modernos
- **Ligero**: Menos de 500KB total
- **Rápido**: Carga instantánea

## 🎨 Paleta de Colores

- Azul: `#3182ce`
- Verde (obtenido): `#10B981`
- Rojo (repes): `#e53e3e`
- Negro/Gris: `#2d3748`
- Background: `#FFFFFF`

## 📞 Soporte

Si tienes problemas o preguntas, por favor abre un issue en GitHub.

---

**¡Disfruta gestionando tu colección de cromos de LaLiga! ⚽**
