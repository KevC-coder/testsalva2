# TESALVA · Aula de práctica v3.0

Web estática basada en el manual **Taller de habilidades para estabilización y transporte del neonato en El Salvador — TESALVA** (2017).

## Banco de preguntas

**240 preguntas: 8 módulos × 30 preguntas**, divididas en **10 básicas, 10 intermedias y 10 avanzadas por módulo**. Cada pregunta presenta cuatro opciones, respuesta correcta, explicación y referencia a la página del manual.

El nivel básico conserva las 80 preguntas de v1. El nivel avanzado conserva las 48 preguntas de v2 y las amplía con 32 preguntas, hasta un total de 80. Se añade el nivel intermedio con 80 preguntas nuevas.

Incluye resultados y puntuaciones por nivel y módulo, respuestas y avance guardados en `localStorage`, repaso de errores y posibilidad de repetir evaluaciones. Los IDs anteriores se conservan para no perder progreso al actualizar desde v2.

## Instalar en GitHub Pages

1. Sube todos los archivos de esta carpeta a la raíz del repositorio de GitHub.
2. En **Settings → Pages**, selecciona **Deploy from a branch**, rama `main`, carpeta `/(root)`.
3. Abre la URL publicada por GitHub.

No requiere dependencias, compilación ni backend. Para actualizar desde v2, reemplaza los archivos conservando el origen del sitio para mantener los datos del navegador.

## Edición

`questions.json` es la versión editable. `questions.js` contiene el mismo contenido para uso directo desde `index.html` incluso sin servidor. Los cambios deben reflejarse en ambos archivos. La clave de progreso es `tesalva-aula-v1` y se mantiene para la compatibilidad.

## Precaución

Autoevaluación educativa **no oficial** basada en un manual de **2017**. Las cifras, criterios y procedimientos no deben utilizarse para tomar decisiones clínicas actuales sin validar los protocolos vigentes y supervisión profesional.
