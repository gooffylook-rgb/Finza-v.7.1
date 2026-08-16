# Finza.M v5.9.9.3 - PWA

Plataforma integral de gestion para el sector no estatal cubano.

## Estructura de archivos

```
finza-m/
  index.html
  manifest.json
  sw.js
  icon.svg
  README.md
```

## Activar GitHub Pages

1. Suba todos los archivos a la raiz del repositorio.
2. Settings > Pages.
3. Source: Deploy from a branch.
4. Branch: main / root > Save.
5. La app estara en: https://SU-USUARIO.github.io/NOMBRE-REPO/

## Uso offline

La primera carga requiere internet (para descargar jsPDF).
Despues, el Service Worker cachea todo y funciona sin conexion.