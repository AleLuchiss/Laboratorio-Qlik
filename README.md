# Laboratorio Qlik Sense

Sitio interactivo para aprender y practicar los conceptos de los capítulos 1 a 4 del libro **Qlik Sense® Cookbook** (Philip Hand y Neeraj Kharpate, Packt, 2015).

Cada lección explica una idea del libro y trae un laboratorio: se cambia una opción y se ve cómo responde el script, el modelo de datos o el gráfico. Cada módulo termina con un cuestionario corto.

🔗 **Sitio publicado:** [laboratorio-qlik.vercel.app](https://laboratorio-qlik.vercel.app) <!-- reemplazar por la URL definitiva -->

## Contenido

| Módulo | Tema | Laboratorios |
|---|---|---|
| 1 · Datos | Conectar, revisar y reutilizar | Tipos de conexión y script resultante · Data model viewer (ceros a la izquierda, duplicados) · Medidas maestras vs. fórmulas copiadas |
| 2 · Visualizaciones | De la pregunta al gráfico | Método DAR · Elección de gráfico por tipo de pregunta · Colores persistentes y `ColorMix1` · Snapshot vs. bookmark |
| 3 · Scripting | Ordenado, reutilizable y rápido | Generador de encabezados · `Include` vs. `Must_Include` · Carga optimizada de QVD · Flags · `For Each` vs. comodín · `Concat()` |
| 4 · Apps e interfaz | Publicar y dar contexto | Ciclo de vida de una app publicada · KPI con gauge y líneas de referencia · Banda de control, `Fractile()` y límite de eje |

Cada módulo incluye un cuestionario de 4 o 5 preguntas con la explicación de cada respuesta. El mejor resultado se guarda en el navegador (`localStorage`) y se muestra en el índice.

## Tecnología

- Un solo archivo `index.html`: HTML, CSS y JavaScript sin frameworks ni dependencias.
- Gráficos dibujados en SVG desde el propio script.
- Tipografías de Google Fonts (IBM Plex Sans, IBM Plex Sans Condensed y JetBrains Mono).
- Modo claro y oscuro automático según el sistema operativo.
- Diseño adaptable a celular.

## Uso local

No necesita instalación: basta con abrir `index.html` en el navegador.

## Publicación en Vercel

El sitio es estático, así que se publica sin paso de build.

**Desde GitHub:** importar el repositorio en Vercel (**Add New › Project**), con **Application Preset: Other**, **Root Directory** `./` y sin comando de build. Cada push a `main` vuelve a publicar el sitio.

**Desde la terminal:**

```bash
npm install -g vercel
vercel login
vercel --prod
```

## Sobre el libro

Este laboratorio resume y adapta el contenido del libro con ejemplos propios. **No incluye el libro ni fragmentos extensos de él**, que tiene derechos de autor.

- *Qlik Sense® Cookbook*, Philip Hand y Neeraj Kharpate. Packt Publishing, 2015. ISBN 978-1-78217-514-8.
- Existe una segunda edición (2018).
- Documentación oficial: [help.qlik.com](https://help.qlik.com/)

Los datos de los ejemplos (unidades, pozos, áreas y valores) son ficticios.

## Autor

Alejandro Arce · Consultor BI
