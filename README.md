# EBENEZER Cleaning Services — PWA
## ESIBAC AI Intelligent Solutions · Better Results

---

## 🚀 Instalación en 3 pasos

### Opción A — Uso inmediato (sin servidor)
1. Descarga y descomprime el archivo ZIP
2. Abre `index.html` directamente en tu navegador
3. (Para instalación como app, necesitas HTTPS — ver Opción B)

### Opción B — Servidor local (recomendado para instalación PWA)
```bash
# Con Python (ya instalado en Mac/Linux):
python3 -m http.server 8080
# Abre: http://localhost:8080

# Con Node.js:
npx serve .
```

### Opción C — Hosting gratuito (para uso internacional)
Sube los archivos a:
- **Netlify**: arrastra la carpeta a netlify.com/drop → URL pública instantánea
- **Vercel**: `npx vercel` en la carpeta
- **GitHub Pages**: push al repositorio → Settings → Pages

---

## 📲 Instalar como app en el dispositivo

### En Android (Chrome):
1. Abre la URL de la app
2. Chrome mostrará "Agregar a pantalla de inicio" en la barra inferior
3. Toca "Instalar" — se instala como app nativa sin App Store

### En iPhone/iPad (Safari):
1. Abre la URL en Safari
2. Toca el botón de compartir (cuadrado con flecha)
3. Selecciona "Agregar a pantalla de inicio"
4. Toca "Agregar"

### En computadora (Chrome/Edge):
1. Abre la URL
2. Verás un ícono de instalación en la barra de direcciones (➕ o ⊕)
3. Haz clic e instala — se abre como aplicación de escritorio

---

## 🔑 Credenciales de acceso

### Administrador
| Usuario | Contraseña |
|---------|-----------|
| `admin` | `admin123` |

### Empleados (demo)
| Usuario | Contraseña | Nombre |
|---------|-----------|--------|
| `maria.gonzalez` | `maria2025` | María González |
| `carlos.reyes` | `carlos2025` | Carlos Reyes |
| `sofia.mendez` | `sofia2025` | Sofía Méndez |
| `luis.flores` | `luis2025` | Luis Flores |

---

## 🤖 Configurar IA (ChatGPT)

1. Obtén tu API key en: https://platform.openai.com/api-keys
2. Abre `index.html` en un editor de texto
3. Busca la línea: `let aiApiKey = 'sk-proj-REPLACE_WITH_YOUR_OPENAI_API_KEY';`
4. Reemplaza el valor con tu API key real
5. Guarda el archivo

---

## 🌍 Idiomas disponibles
- Español (default)
- English
- Português
- Français

---

## 📁 Estructura de archivos
```
ebenezer-app/
├── index.html        ← Aplicación completa
├── manifest.json     ← Configuración PWA instalable
├── sw.js             ← Service Worker (offline + install)
├── icons/
│   ├── icon-192.png  ← Ícono app
│   └── icon-512.png  ← Ícono splash
└── README.md         ← Este archivo
```

---

## ✨ Funcionalidades incluidas

**Panel Administrador:**
- Dashboard con métricas y rendimiento
- Agendar citas con mapa Google Maps integrado
- Gestión de empleados (agregar, editar)
- Vista de disponibilidad por bloques horarios
- Trabajos activos en tiempo real
- Registro fotográfico por trabajo
- Centro de notificaciones (WhatsApp + Correo)
- Retroalimentación y reseñas de clientes
- Asistente IA (ChatGPT GPT-4o)

**Panel Empleado:**
- Mis citas del día con dirección y mapa
- Subida de fotos (inicio / proceso / final)
- Campo de observaciones y notas
- Perfil personal con calificaciones
- Estadísticas del mes

---

## 🔧 Personalización

Para cambiar el nombre de la empresa u otros datos:
- Busca "EBENEZER" en index.html y reemplaza según necesites
- Los colores están en `:root` al inicio del CSS (`--red`, `--blue`)

---

**ESIBAC AI Intelligent Solutions · Better Results**
