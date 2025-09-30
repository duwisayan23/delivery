Planificación de Sprint Semanal – Aplicación Delivery
Este documento presenta una planeación de sprint con duración de 1 semana para una aplicación de delivery. Incluye las fases de planificación, codificación, integración, entrega, despliegue, monitoreo y retroalimentación.
Día 1 – Planificación
- Revisión del backlog de producto (nuevas features, bugs, mejoras).
- Refinamiento de requisitos (user stories claras con criterios de aceptación).
- Estimación rápida (planning poker o T-shirt sizes).
- Selección de lo que entra en el sprint (con base en capacidad del equipo).
- Definición del objetivo del sprint (ejemplo: mejorar UX de pagos).
- Configuración de tareas en tablero (Jira/Trello).

Entregable: Sprint backlog definido.
Días 2 a 4 – Codificación (Desarrollo)
- Desarrollo de nuevas funcionalidades (ej. tracking de pedidos en tiempo real).
- Corrección de bugs de la versión anterior.
- Implementación de pruebas unitarias y de integración.
- Code review entre pares.
- Actualización de documentación técnica.

Entregable: Código funcional y probado en entorno local.
Día 5 – Integración
- Merge a rama principal (main/master).
- Ejecución de pipeline CI/CD:
   * Compilación automática.
   * Pruebas automatizadas (unitarias + integración + end-to-end).
   * Análisis estático de código (SonarQube, Lint).
- Preparación de release candidate.

Entregable: Versión candidata lista en entorno de staging.
Día 6 – Entrega y Despliegue
- Validación en staging con QA/PO:
   * Pruebas funcionales.
   * Validación de usabilidad.
   * Revisión de criterios de aceptación.
- Ajustes menores.
- Despliegue en producción mediante CI/CD (Google Play Console/TestFlight o despliegue web).
- Comunicación del release (notas de actualización internas y para usuarios).

Entregable: Versión en producción.
Día 7 – Monitoreo y Realimentación
- Monitoreo en producción:
   * Logs y métricas de rendimiento (Firebase, Datadog, New Relic).
   * Seguimiento de errores (Sentry, Crashlytics).
   * Monitoreo de uso (Google Analytics/Amplitude).
- Recolección de feedback de usuarios (reseñas, encuestas, soporte).
- Retroalimentación del equipo (retrospectiva corta).
- Preparación de backlog para el siguiente sprint.

Entregable: Reporte de métricas + feedback documentado.
