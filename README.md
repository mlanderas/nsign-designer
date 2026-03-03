# nsign Applet Designer

**Herramienta visual para disenar y exportar applets HTML5 para [nsign.tv](https://nsign.tv)**

![Version](https://img.shields.io/badge/version-1.0.0-7C6AFF)
![Standalone](https://img.shields.io/badge/standalone-sin%20dependencias-22C55E)
![License](https://img.shields.io/badge/license-MIT-blue)

## Que es?

Un unico fichero HTML que abre directamente en el navegador (sin instalacion, sin servidor):

- Disenar pantallas de carteleria digital con texto, imagenes, video y formas
- Conectar campos de texto a fuentes de datos externas: CSV, API REST, SSE o WebSocket
- Exportar un applet HTML5 listo para subir a nsign.tv
- Guardar y recuperar proyectos

## Inicio rapido

1. Descarga `nsign-designer.html`
2. Abrelo en Chrome o Edge
3. Disena, conecta datos, exporta

## Fuentes de datos

| Tipo | Autenticacion |
|------|---------------|
| CSV | - |
| API REST | Sin auth, API Key, Bearer, Basic |
| SSE | Sin auth, API Key, Bearer, Basic |
| WebSocket | Sin auth, Bearer via URL |

## Estructura

```
nsign-designer.html
examples/
  applet-csv-filtro.html
  productos.csv
docs/
  manual-nsign-designer.docx
CHANGELOG.md
```

## Licencia

MIT
