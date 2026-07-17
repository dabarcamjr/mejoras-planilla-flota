# Auditoría del Sistema Documental de Flota · Transportes Zamora

Sitio web con la **auditoría integral** del sistema de gestión documental de la flota: 19 planillas de
control (Google Sheets) y ~3.155 PDFs de evidencia. Incluye el mapa del sistema, hallazgos por área y una
hoja de ruta con las mejoras priorizadas de la más urgente a la menos importante.

🌐 **Publicado en:** https://dabarcamjr.github.io/mejoras-planilla-flota/

## Páginas

| Archivo | Contenido |
|---|---|
| `index.html` | Portada: resumen, mapa del sistema, inventario de las 19 planillas y las 14 mejoras priorizadas (visión global). |
| `documentacion.html` | Núcleo: Planillas Madre (Flota y Personas) + acreditaciones por cliente + matriz de requisitos. |
| `operacion.html` | Checklists, control de ingreso, taller y los ~3.197 PDFs de evidencia. |
| `mantencion.html` | Mantenciones por km, órdenes de trabajo y neumáticos. |
| `combustible.html` | Cargas de combustible y cruce con RFID. |
| `administracion.html` | Órdenes de compra/facturas, depósitos, Apps Script de carpetas y dominios ajenos. |
| `styles.css` | Hoja de estilos compartida (tema claro/oscuro). |

## Publicar / actualizar

El sitio es estático (HTML + CSS, sin dependencias). Se publica con GitHub Pages desde la rama `main`,
carpeta raíz. Al hacer `git push`, los cambios se reflejan en 1–2 minutos.
