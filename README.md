# Web Victor

Proyecto web estático para publicar juguetes en venta.

## Requisitos

- Node.js 22 (recomendado, ver `.nvmrc`)
- npm 10+

## Desarrollo (macOS y WSL)

1. Instala la versión de Node recomendada:
   - Con `nvm`: `nvm install && nvm use`
2. Instala dependencias:
   - `npm install`
3. Levanta el servidor local:
   - `npm run dev`
4. Abre:
   - `http://localhost:5173`

## Build de producción

- `npm run build`
- Salida: `dist/`

## Previsualizar build

- `npm run preview`
- URL: `http://localhost:4173`

## Notas para WSL

- Trabaja dentro del sistema de archivos Linux (`~/...`) para mejor rendimiento.
- Si quieres abrir desde Windows, usa `http://localhost:5173` en tu navegador de Windows.

## Notas para macOS

- Si el puerto 5173 está ocupado, libera el puerto o cambia `vite.config.js`.
- El proyecto usa finales de línea LF para evitar conflictos con WSL (`.gitattributes` + `.editorconfig`).
