# nsign Applet Designer

**Herramienta visual para diseñar y exportar applets HTML5 para [nsign.tv](https://nsign.tv)**

![Version](https://img.shields.io/badge/version-1.0.0-7C6AFF)
![Standalone](https://img.shields.io/badge/standalone-sin%20dependencias-22C55E)

## ¿Qué es?

Un único fichero HTML que abre directamente en el navegador (sin instalación, sin servidor) y permite:

- 🎨 **Diseñar** pantallas de cartelería digital con texto, imágenes, vídeo y formas
- 🔌 **Conectar** campos de texto a fuentes de datos: CSV, API REST, SSE o WebSocket
- 📦 **Exportar** un applet HTML5 listo para subir a nsign.tv
- 💾 **Guardar y recuperar** proyectos (.nsignproj)

## Inicio rápido

1. Descarga `nsign-designer.html`
2. Ábrelo en Chrome o Edge
3. Diseña, conecta datos, exporta

## Fuentes de datos

| Tipo | Autenticación |
|------|--------------|
| CSV | — |
| API REST | Sin auth / API Key / Bearer / Basic |
| SSE (streaming) | Sin auth / API Key / Bearer / Basic |
| WebSocket | Sin auth / Bearer via URL |

## Mapeo JSON

- **Ruta**: `data.items[0].precio`
- **Filtrar array**: campo=valor → otro campo
- **Template**: `{nombre} — {precio}€`

## Estructura

```
nsign-designer.html          ← La herramienta
examples/
  applet-csv-filtro.html     ← Ejemplo CSV
  productos.csv              ← CSV de ejemplo
docs/
  manual-nsign-designer.docx ← Manual completo
CHANGELOG.md
```

## Versiones

Ver [CHANGELOG.md](CHANGELOG.md) · [Releases](../../releases)
