# Plan de Riesgos
## Proyecto: Query & Coffee

El objetivo de este plan es identificar, evaluar y establecer estrategias formales de mitigación para los riesgos técnicos y operativos del proyecto. Toda la gestión, calificación exhaustiva de probabilidades e impactos, y las directrices principales se encuentran centralizadas en el archivo **[Riesgos_Final.xlsm](file:///c:/APTI/Riesgos_Final.xlsm)**. Este libro de Excel con macros funciona como el Registro Oficial de Riesgos del proyecto y es el documento maestro sobre el cual se sustenta la continuidad operativa y la matriz que se presenta a continuación.

### Matriz de Riesgos y Estrategias Sugeridas

A continuación se listan los 15 riesgos identificados para el proyecto y la directriz formal de mitigación asignada para cada uno:

| ID | Riesgo Identificado | Estrategia de Administración (Directriz de Mitigación) |
|:---|:---|:---|
| R-01 | **Subrepresentación de la muestra en encuestas** | Ejecutar una campaña híbrida (física con QR y difusión digital). Solicitar a docentes apoyo para invitar a participar durante clases. |
| R-02 | **Integridad y ruido en datos recolectados (spam/duplicados)** | Implementar validaciones lógicas en el formulario (ej. reCAPTCHA) y programar scripts en el proceso ETL para eliminar duplicados. |
| R-03 | **Falla de infraestructura crítica (equipos de cómputo)** | Mantener respaldos diarios del código y de los datos en repositorios seguros en la nube (GitHub, Supabase). |
| R-04 | **Compromiso de privacidad y anonimato de participantes** | Auditar el diseño del instrumento para garantizar que no se soliciten correos ni números de boleta, cumpliendo con la LFPDPPP. |
| R-05 | **Cuello de botella en ruta crítica (desarrollo Dashboard)** | Aplicar metodología ágil (Scrum) con Daily Standups para identificar bloqueos técnicos y priorizar el desarrollo de un MVP. |
| R-06 | **Baja permisividad institucional para colocar códigos QR** | Gestionar y firmar un oficio formal de autorización con la Dirección de la ESCOM antes de iniciar la recolección en campo. |
| R-07 | **Dependencia de plataformas de hosting externas** | Utilizar una arquitectura agnóstica para permitir una migración rápida a otro proveedor si el actual presenta caídas. |
| R-08 | **Sesgo en las respuestas por grupos de interés** | Diseñar preguntas neutrales y aplicar técnicas en el EDA para identificar y separar anomalías de opinión. |
| R-09 | **Rotación o baja de un miembro clave del equipo** | Mantener documentación técnica exhaustiva y control de versiones para asegurar un onboarding rápido de reemplazos. |
| R-10 | **Desajuste en el presupuesto por alza en costo de hardware** | Realizar cotizaciones y compras del hardware durante las primeras semanas del proyecto para congelar precios. |
| R-11 | **Falta de validación estadística del instrumento (encuesta)** | Aplicar una prueba piloto a un grupo de control antes del lanzamiento masivo para ajustar reactivos confusos. |
| R-12 | **Incumplimiento de plazos en la fase de análisis EDA** | Dividir la fase de análisis en Sprints semanales, enfocándose primero en las variables más urgentes (precio e higiene). |
| R-13 | **Pérdida o corrupción de datos durante el proceso ETL** | Configurar backups automáticos de la base de datos cruda y utilizar control de versiones para los scripts SQL/Python. |
| R-14 | **Rechazo o baja adopción del dashboard por la administración** | Realizar sesiones de codiseño y demostración tempranas con los usuarios finales para retroalimentación de UI/UX. |
| R-15 | **Conflicto de intereses con concesionarios al publicar resultados** | Garantizar que el manejo del Dashboard sea confidencial para el Patrocinador; no publicar datos crudos al público sin autorización. |

### Monitoreo de Riesgos
Los riesgos serán evaluados y monitoreados de manera continua por los Project Managers durante las reuniones semanales de seguimiento del cronograma, aplicando la directriz dictada para cada riesgo específico en caso de materializarse.
