# Alcalde Digital — página de descarga

Página del juego: https://alcalde-digital-juego.vercel.app/

- La página es estática (HTML, CSS y un JS pequeño), sin cookies ni rastreadores.
- Las descargas están en [Releases](../../releases/latest). Las construye `.github/workflows/instaladores.yml`
  a partir del proyecto del juego.

Para publicar una versión nueva: `gh workflow run instaladores.yml -f commit=<SHA> -f version=v1.0.1`
