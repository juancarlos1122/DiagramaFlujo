# DiagramaFlujo


Este es el diagrama de flujo para la automatización de procesos en nuestra planta:

```mermaid
flowchart TD
    A[Recepción de Ideas de Automatización (Buzón de Entrada)] --> B[Revisión y Evaluación de Viabilidad de las Ideas]
    B --> C[Planificación de la Automatización y Gestión del Cambio (MOC)]
    C --> D[Diseño y Desarrollo de la Solución de Automatización]
    D --> E[Implementación de la Solución de Automatización]
    E --> F[Monitoreo y Seguimiento Post-Implementación]
    F --> G[Evaluación de Resultados y Mejora Continua]
