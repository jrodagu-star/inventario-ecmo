# Inventario UCC · Asistencia circulatoria mecánica

Aplicación web para el inventario de una unidad de cuidados críticos cardiológicos especializada en shock cardiogénico y asistencias mecánicas (ECMO, Impella y balón de contrapulsación).

La sesión del 26 de octubre de 2026 ya va cargada: 290 ítems. El escenario de esa copia es 2 camas (1 con asistencia, 1 de reserva y 0 para shock sin asistencia), 1 paciente simultáneo con asistencia, 1 en shock, 7 días de duración media y 1 paciente al mes.

## Abrir la aplicación

No hace falta instalar nada. Sirve la carpeta como sitio estático y abre la raíz, o abre `index.html` en el navegador.

En GitHub Pages la página se publica desde la raíz de `main`. El archivo `.nojekyll` evita que Jekyll altere el HTML.

## Datos

La aplicación lee la sesión embebida en `index.html` (`#savedData`), que es el formato de «Guardar copia» de la propia herramienta.

`data/inventario_ucc_sesion.json` es la misma sesión. Se puede volver a importar desde el botón de importar de la barra lateral.

Dentro de la aplicación se puede exportar de nuevo la sesión (JSON), una copia HTML autónoma, un CSV o el informe en PDF.
