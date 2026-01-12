# Vue Tarea 6.1.1

Aplicación Vue (sin componentes de un solo archivo) que muestra y permite editar los datos de una persona.

## Estructura
- `index.html`: App Vue cargada por CDN, plantilla y lógica (Options API: `data`, `methods`).
- `styles.css`: Estilos tomados del ejercicio React para reproducir el diseño.

## Cómo ejecutar
1. Servidor HTTP (ya disponible en tu entorno bajo `localhost`).
2. Abre en el navegador:
   - `http://localhost/DWEC/UT06/Tarea6_1_1/Vue/`

## Notas
- Sin SFC: no hay `.vue` ni tooling (Vite/Webpack). Solo HTML+CSS+JS y Vue CDN.
- Formulario con `v-model` y envío con `@submit.prevent` para copiar `formPersona` a `persona`.
