# Proyecto Final

Este repositorio contiene los archivos principales del proyecto web "Proyecto Final" (cliente). 

## Estructura principal

- `index.html` — Página principal.
- `main.css` — Estilos.
- `main.js` — Lógica y arranque de la aplicación.
- `build/` — Bibliotecas preempaquetadas (Three.js y variantes).
- `src/` — Código fuente y módulos utilizados por la aplicación.
  - `src/jsm/` — Contiene módulos de Three.js y controles auxiliares (no incluidos en este repo, ver nota abajo).

## Nota importante sobre `src/jsm`

La carpeta `src/jsm` no se encuentra incluida en este repositorio. No se pudo subir al repositorio en GitHub debido a políticas/restricciones aplicadas (por ejemplo, relativas a licencia, tamaño o directrices de contenido). Si necesitas los módulos que normalmente estarían en `src/jsm`, puedes:

- Descargar la carpeta `jsm` desde la fuente oficial de Three.js y copiarla en `src/jsm` localmente.
- O instalar Three.js y los módulos correspondientes desde npm si prefieres un flujo con gestor de paquetes.

Nota: Si vas a clonar este repositorio en otra máquina, recuerda agregar manualmente la carpeta `src/jsm` o usar npm para instalar dependencias antes de ejecutar el proyecto.

## Versión en vivo

- Versión en vivo: https://szl9lm.csb.app/
