# proteccion-seguridad — Protección y Seguridad

**Responsable:** Coordinación de Protección y Seguridad.

## Para qué sirve

App HTML de **reportes y seguimiento** para roles de **responsable** y **supervisor** de protección y seguridad: captura de reportes, historial, vista de desempeño y administración (actividades, responsables, ajustes).

## Archivo principal en este repo

- `index.html` — aplicación completa (PWA-ready: manifest, theme-color).

## Quién lo usa

Responsables (reporte / historial) y supervisores (dashboard, desempeño, historial, admin).

## Cómo se usa

Abrir la app publicada (GitHub Pages) o el `index.html` localmente. Iniciar sesión según el rol configurado en la app. Capturar reportes, consultar historial y, en supervisor, administrar catálogos.

## Dónde se guardan los datos y cómo respaldar

Datos en la nube (**Firebase** Firestore): colección de reportes y documentos de configuración. Exportación con librerías **SheetJS (xlsx)** y **JSZip**. **No** publicar claves de Firebase en el README.

## Publicación

- Repo: https://github.com/cervantsgarc92-lab/proteccion-seguridad  
- **GitHub Pages:** https://cervantsgarc92-lab.github.io/proteccion-seguridad/

## Relación con otras apps

No confundir con **Servicio de Seguridad al albergue** (otra app, en Netlify: `proteccionysegbot.netlify.app`), ni con el **Tablero/encuesta de Jefes de Turno**.

## Limitaciones

- Sin README previo en el repo (este archivo lo cubre).
- Último commit del inventario: jun 2026 — conviene versionar cambios activos.
