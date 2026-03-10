# Antropoeggers Web

Este repositorio contiene la versión completa y conectada del sitio web principal y el MVP interactivo de diagnóstico para **Antropoeggers**, un portafolio de servicios que combina Antropología, Quality Assurance (QA) y Desarrollo con Inteligencia Artificial.

## 🚀 Arquitectura del Proyecto

El proyecto está compuesto por páginas estáticas construidas con HTML5 puro y TailwindCSS a través de un CDN, asegurando alta velocidad y nulo tiempo de compilación para despliegues rápidos. No requiere base de datos de momento, pero su interfaz está lista para conectarse.

### Archivos Principales

1.  **`index.html`**
    *   **Landing Page y Portafolio:** Presenta la UVP (Propuesta Única de Valor), los servicios (Incubación MVP, QA Sostenible, Auditoría Antropo-UX) y el contacto.
    *   **Estilo:** Utiliza diseño *Glassmorphism*, gradientes y animaciones sutiles.
    *   **Interacción:** Contiene un botón principal en el Hero *"Evaluar mi Proyecto"* que redirige directamente a la herramienta de diagnóstico.

2.  **`dianostico.html`**
    *   **Herramienta de Diagnóstico MVP:** Un cuestionario interactivo escrito en JavaScript puro que evalúa la madurez técnica y viabilidad de un proyecto.
    *   **Gamificación:** El cuestionario consta de 5 preguntas (Unidad de dolor, Happy Path, Oráculo, etc.).
    *   **Tematización Dinámica:** Según el puntaje del usuario, la página cambia todo su color y estilo para reflejar uno de los tres perfiles: *Soñador (Naranja)*, *Planificador (Cian)* o *Ejecutor (Verde)*.
    *   **Flujo:** Implementa un botón "Volver" fijado en la pantalla para regresar ágilmente al `index.html`. 

## 🎨 Aspectos Destacados UI/UX

*   Animación de partículas de fondo renderizadas en `<canvas>`.
*   Tipografía moderna (`Plus Jakarta Sans`, `Space Grotesk`, `JetBrains Mono`).
*   Íconos FontAwesome.
*   Diseño Responsivo (Mobile First).

## 🛠️ Contribución y Despliegue

Este proyecto está listo para ser desplegado en servicios de hosting de sitios estáticos como:
*   GitHub Pages
*   Vercel
*   Netlify

Para trabajar en local, simplemente abre el archivo `index.html` en cualquier navegador moderno. No requiere usar `npm` ni iniciar un servidor local (`localhost`).

---
"El código es el medio, el humano es el fin." - *Antropoeggers*
