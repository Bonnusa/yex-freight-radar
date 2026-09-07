# Yex Freight Radar

**App en vivo / Live app:** https://bonnusa.github.io/yex-freight-radar/

Herramienta para Yex, freight broker en Savannah, Georgia: dónde buscar clientes (shippers) y transportistas (carriers) en la Costa Este, con dry van, flatbed y hot shot. No cubre contenedores.

A tool for Yex, a freight broker based in Savannah, Georgia: where to find shippers and carriers on the East Coast, for dry van, flatbed and hot shot. Containers are out of scope.

## Qué incluye / What's inside

- **Mercados / Markets** — mapa de estados por calor de carga saliente y temporada; la Costa Este en color.
- **Clientes / Shippers** — búsquedas listas por estado, ciudad, equipo e industria.
- **Transportistas / Carriers** — verificación FMCSA (SAFER, L&I, SMS), checklist y búsquedas.
- **Pipeline** — prospectos con etapas y seguimientos, guardados en el navegador con respaldo copiable.
- **Guiones / Scripts** — llamadas en frío, preguntas de calificación, objeciones y rutina semanal.
- Bilingüe ES / EN con un botón en la cabecera.

## Uso / Usage

Es un solo archivo, `index.html`, sin dependencias ni build. Ábrelo en cualquier navegador o publícalo como página estática.

Single file, `index.html`, no dependencies and no build step. Open it in any browser or host it as a static page.

## Notas

- El calor por estado es una estimación por patrones estacionales típicos, no datos en vivo. Confirmar en DAT Trendlines antes de cotizar.
- Los prospectos viven en `localStorage` del navegador; usa "Respaldo" para copiarlos a otro dispositivo.
