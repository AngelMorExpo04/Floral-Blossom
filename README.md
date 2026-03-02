# Floral-Blossom
# 🌸 Floral Bloom — Arte Generativo con Canvas

> Transforma cualquier imagen en una composición artística donde cientos de flores brotan desde el centro hacia los bordes, reproduciendo fielmente los colores de tu foto.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Sin dependencias](https://img.shields.io/badge/dependencias-ninguna-brightgreen?style=flat)

---

## ¿Qué hace?

Floral Bloom es una herramienta de arte generativo que funciona directamente en el navegador, sin instalación ni servidor. Carga una imagen local y el programa la convierte en un mosaico floral animado: cada flor nace en el centro de la imagen y crece radialmente hacia los bordes, usando como color exactamente el pixel de la fotografía en esa posición.

El resultado es una imagen artística donde la foto original se puede reconocer, pero construida enteramente con flores.

---

## ✨ Características

- **Colores fieles a la foto** — cada flor promedia el color real de la región de la imagen donde aparece, sin paletas artificiales
- **Animación progresiva** — las flores brotan desde el centro hacia afuera en tiempo real
- **Cobertura completa garantizada** — el grid de flores se adapta automáticamente al tamaño elegido para que no quede ningún hueco, independientemente del tamaño de flor
- **Empaquetado hexagonal** — las flores se distribuyen en filas alternas para una cobertura más uniforme y natural
- **Descarga en PNG** — exporta el resultado final en alta resolución
- **Sin dependencias** — un único archivo `.html` que funciona al abrirlo, sin npm, sin librerías externas

---

## 🎛️ Controles

| Slider | Descripción |
|---|---|
| **Tamaño flor** | Radio de cada flor en píxeles (5–80px) |
| **Cobertura %** | Solapamiento entre flores; 100% = se tocan, 150% = se superponen |
| **Pétalos** | Número de pétalos por flor (3–14) |
| **Velocidad** | Rapidez de la animación de crecimiento |
| **Opacidad** | Transparencia global de las flores |
| **Brillo color** | Boost de saturación sobre el color original (0 = color exacto de la foto) |

---

## 🚀 Uso

1. Descarga el archivo `flower-bloom.html`
2. Ábrelo en cualquier navegador moderno (Chrome, Firefox, Safari, Edge)
3. Arrastra una imagen o haz clic para seleccionarla
4. Ajusta los sliders al gusto
5. Pulsa **↺ Re-generar** para probar distintas configuraciones
6. Cuando estés conforme, pulsa **↓ Descargar PNG**

No requiere conexión a internet una vez descargado el archivo.

---

## 🛠️ Tecnologías

- **Canvas API** — renderizado 2D de flores y gradientes
- **FileReader API** — carga de imágenes locales sin servidor
- **getImageData** — muestreo de color píxel a píxel desde la imagen original
- **requestAnimationFrame** — animación fluida sincronizada con el refresco de pantalla
- **Vanilla JavaScript** — sin frameworks ni librerías

---

## 💡 Tips para mejores resultados

- Imágenes con **colores contrastados** (paisajes, flores reales, retratos) producen los efectos más llamativos
- Con **Tamaño pequeño (5–12px) + Cobertura 130%** la imagen original se reconoce con claridad
- Con **Tamaño grande (40–80px) + Cobertura 90%** el efecto es más abstracto y pictórico
- **Brillo color en 0** respeta los colores exactos de la foto; sube a 20–30 para tonos más vibrantes

---

## 📄 Licencia

MIT — libre para usar, modificar y distribuir.
