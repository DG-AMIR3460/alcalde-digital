# Alcalde Digital — página de descarga

Página del juego: https://dg-amir3460.github.io/alcalde-digital/

- La página es estática (HTML, CSS y un JS pequeño), sin cookies ni rastreadores.
- Las descargas están en [Releases](../../releases/latest). Las construye `.github/workflows/instaladores.yml`
  a partir del repositorio del juego, https://github.com/SebastianBlanco430/Alcalde-Digital.

Para publicar una versión nueva: `gh workflow run instaladores.yml -f commit=<SHA> -f version=v1.0.1`
