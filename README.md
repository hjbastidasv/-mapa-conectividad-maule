
# Mapa de Conectividad - Región del Maule

Este proyecto muestra un mapa interactivo con el estado de conectividad de los 13 hospitales de la Región del Maule (Chile), usando Leaflet.js y una hoja de cálculo de Google Sheets como backend.

## 🛠 Cómo funciona

- Cada hospital tiene una posición geográfica (lat/lon) y un estado de conectividad.
- El estado se almacena en una hoja de Google Sheets.
- El mapa consulta la hoja cada 5 minutos y actualiza automáticamente.

## 🔗 Fuente de datos

Los datos se obtienen de esta hoja de cálculo:

[Google Sheet](https://docs.google.com/spreadsheets/d/1vvcetFFagMr0uPYJ7sYnWVmT3lYXIKWF)

JSON público:  
`https://opensheet.vercel.app/1vvcetFFagMr0uPYJ7sYnWVmT3lYXIKWF/Hospitales`

## 🚀 Publicación con GitHub Pages

1. Crea un repositorio en GitHub, por ejemplo `mapa-conectividad-maule`.
2. Sube `index.html` a la raíz del repositorio.
3. En GitHub:
   - Ve a Settings → Pages
   - Elige la rama `main` y carpeta `/ (root)`
4. Tu mapa estará en:

```
https://TU_USUARIO.github.io/mapa-conectividad-maule/
```

---

Desarrollado con ❤️ y Leaflet.js
