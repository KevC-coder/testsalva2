# TESALVA · Aula de práctica

Web estática de autoevaluación basada en **Taller de habilidades para estabilización y transporte del neonato en El Salvador — TESALVA** (Ministerio de Salud / ISSS, octubre de 2017).

## Contenido

- 8 módulos, 80 preguntas (10 por módulo), 4 opciones por pregunta.
- Envío y calificación del módulo, revisión de aciertos y errores con explicación y página de referencia.
- Repetición y práctica de preguntas falladas.
- Guardado local de progreso mediante `localStorage` (no se envían respuestas a un servidor).
- Diseño responsive, sin framework ni backend.

## GitHub Pages

1. Crea un repositorio en GitHub, por ejemplo `tesalva-examen`.
2. Sube **los archivos de esta carpeta** a la raíz del repositorio (`index.html`, `styles.css`, `app.js`, `questions.js`, `questions.json` y este README).
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`; guarda.
5. Abre la URL publicada por GitHub Pages.

También puedes ejecutar `index.html` directamente sin servidor, ya que el banco de preguntas se carga desde `questions.js`. La fuente `DM Sans`/`Outfit` requiere internet, pero existe tipografía de reserva del sistema.

## Editar preguntas

Edita los objetos dentro de `questions.js` (variable `window.TESALVA_DATA`). Cada pregunta incluye `id`, `module` (0 a 7), `question`, `options` (4 textos), `answer` (índice 0 a 3), `page` y `explanation`. Si editas `questions.json` también, mantenlo sincronizado con `questions.js`.

## Nota importante

**Herramienta educativa no oficial.** La fuente original es de **2017**. Preguntas, rangos y procedimientos reflejan ese documento y no sustituyen guías, protocolos o formación clínica vigentes. El banco de preguntas se elaboró para repaso y no es una reproducción de los instrumentos oficiales de evaluación.
