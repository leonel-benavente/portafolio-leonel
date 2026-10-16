# Portafolio · Leonel Benavente Quiquisola

Sitio web estático (HTML, CSS y JavaScript, sin compilación) del portafolio de Leonel Benavente, Project Control Engineer · AI Innovation Lead.

## Estructura

```
index.html          Portafolio 3D (página principal)
cv.html             CV formato Stanford (versión web)
cv/                 CV en PDF para descargar
media/              Imágenes, videos del avatar (WebM + MP4) y videos de las demos
torre/index.html    Demo anonimizada · Torre de Control de Portafolio
auditor/index.html  Demo anonimizada · Auditor de Horas-Hombre
altiplano/index.html Demo anonimizada · Altiplano 3D
```

## Publicar en Vercel

- Framework Preset: **Other**
- Build Command: vacío
- Output Directory: vacío (la raíz del repositorio)

Cada cambio que subas a la rama `main` se publica solo.

## Probar en tu computadora

Los videos del avatar se recortan en vivo con WebGL, así que la página debe abrirse desde un servidor, no haciendo doble clic en el archivo:

```
python3 -m http.server 8000
```

y luego abre http://localhost:8000

## Librerías externas (CDN)

- GSAP 3.12.5 + ScrollTrigger (cdnjs)
- Three.js r128 (cdnjs) y OrbitControls 0.128.0 (jsDelivr)
- Chart.js 4.4.1 (cdnjs)
- Google Fonts: Bricolage Grotesque, Hanken Grotesk, Barlow

## Notas

- Las demos están anonimizadas: proyectos, clientes, proveedores y montos reemplazados u ocultos.
- El juego "Obra sin sorpresas" se abre en su enlace de Google Apps Script.
