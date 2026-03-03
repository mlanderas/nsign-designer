# Changelog

Formato: [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/)
Versionado: [semver.org](https://semver.org/lang/es/)

---

## [1.0.0] — 2025-03-03

### Añadido
- Diseñador visual con canvas drag & drop y 8 handles de redimensionado
- Tipos de elemento: Texto, Imagen, Vídeo, Rectángulo, Elipse (editables y estáticos)
- Panel de propiedades: posición, tamaño, tipografía, color, z-index, opacidad
- Animaciones CSS: Fade In/Out, Slide ←→↑
- Resoluciones: FHD 1920×1080, 4K, HD, Vertical 1080×1920, personalizado
- Zoom con ajuste automático al canvas y cuadrícula de referencia
- **Fuente CSV**: carga URL, detección de cabeceras, filtrado columna=valor, preview tiempo real
- **Fuente API REST**: GET periódico configurable con refresco en segundos
- **Fuente SSE**: conexión persistente con reconexión automática cada 5s
- **Fuente WebSocket**: conexión WS/WSS con reconexión automática cada 5s
- Autenticación: Sin auth, API Key (header), Bearer Token, Basic Auth
- Mapeo JSON: Ruta directa, Filtrar array, Template con {campo}
- Sistema CORS con 4 niveles de fallback automático (proxies públicos)
- Botón ▶ Test para probar conexiones en tiempo real desde el designer
- Export HTML con CSS, animaciones y JS de fuentes de datos
- JS exportado optimizado: agrupa peticiones por URL (1 fetch por CSV/API)
- Sistema de proyectos: guardar/cargar en localStorage
- Exportar/importar proyectos como fichero .nsignproj
- Auto-guardado cada 2 minutos con indicador visual (punto amarillo/verde)
- Aviso al cerrar con cambios sin guardar
- Panel de logs con 5 niveles (DEBUG/INFO/WARN/ERR/CSV) y filtrado
- Fix compatibilidad nsign: imágenes con wrapper div + overflow:hidden
- Versión visible en toolbar (v1.0.0)
- Manual de usuario en docs/
