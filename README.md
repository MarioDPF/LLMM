# LLMM
Este repositorio incluye actividades llevadas a cabo en el módulo Lenguaje de Marcas

# Proyecto de prueba

Bienvenido/a al repositorio de prueba. Este README demuestra el uso básico de **Markdown**: cabeceras, texto, listas, un gráfico embebido y una tabla.

## 1. ¿Qué contiene este README?
- Diferentes niveles de cabeceras
- Texto en **negrita** y *cursiva*
- Una lista con viñetas y numerada
- Un gráfico simple (SVG incrustado)
- Una tabla

### Descripción breve
Markdown es una forma rápida de escribir documentos con formato que luego se muestran como HTML. Es ideal para README, documentación, notas y blogs.

## 2. Lista de ejemplo

- Elemento 1
- Elemento 2
  - Sub-elemento 2.1
  - Sub-elemento 2.2
- Elemento 3

1. Paso uno
2. Paso dos
3. Paso tres

## 3. Gráfico (SVG embebido)

<!-- Un gráfico de barras simple en SVG. GitHub renderiza SVG incrustado. -->
<div>
  <svg width="480" height="160" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Gráfico de barras de ejemplo">
    <title>Gráfico de barras de ejemplo</title>
    <!-- fondo -->
    <rect width="100%" height="100%" fill="#ffffff"></rect>

    <!-- ejes -->
    <line x1="40" y1="20" x2="40" y2="120" stroke="#000" stroke-width="1"/>
    <line x1="40" y1="120" x2="440" y2="120" stroke="#000" stroke-width="1"/>

    <!-- barras -->
    <rect x="60" y="50" width="60" height="70" fill="#7fb3ff"></rect>
    <rect x="150" y="80" width="60" height="40" fill="#4facff"></rect>
    <rect x="240" y="30" width="60" height="90" fill="#1f77b4"></rect>
    <rect x="330" y="65" width="60" height="55" fill="#0b5cff"></rect>

    <!-- etiquetas -->
    <text x="90" y="140" font-size="12" text-anchor="middle">A</text>
    <text x="180" y="140" font-size="12" text-anchor="middle">B</text>
    <text x="270" y="140" font-size="12" text-anchor="middle">C</text>
    <text x="360" y="140" font-size="12" text-anchor="middle">D</text>

    <!-- valores -->
    <text x="90" y="45" font-size="12" text-anchor="middle">70</text>
    <text x="180" y="75" font-size="12" text-anchor="middle">40</text>
    <text x="270" y="25" font-size="12" text-anchor="middle">90</text>
    <text x="360" y="60" font-size="12" text-anchor="middle">55</text>
  </svg>
</div>

> Nota: si prefieres usar una imagen (.png/.jpg) en lugar de SVG, súbela al repositorio y usa `![Gráfico](ruta/imagen.png)`.

## 4. Tabla de ejemplo

| Lenguaje | Nivel | Comentarios |
|---------:|:-----:|------------:|
| Python   | Avanzado | Muy usado para análisis |
| JavaScript | Intermedio | Web, frontend/backend |
| Markdown | Básico | Ideal para documentación |

---

## 5. Cómo editar este README
1. Edita localmente `README.md` y haz `git add README.md && git commit -m "Actualizar README"` y `git push`.
2. O haz clic en el botón de lápiz (Edit) en GitHub para editar en línea y luego *Commit changes
