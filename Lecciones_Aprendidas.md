# Lecciones Aprendidas
## Proyecto: Query & Coffee

El registro de lecciones aprendidas tiene como propósito documentar los éxitos, fracasos y oportunidades de mejora descubiertas durante el ciclo de vida del proyecto "Query & Coffee", con el fin de capitalizar este conocimiento para futuras iniciativas tecnológicas dentro del IPN.

### 1. Gestión del Tiempo y Recursos (Pivot Arquitectónico)
*   **Situación:** Originalmente se planeó desarrollar el Dashboard en Power BI.
*   **Lección Aprendida:** Es vital mantener la agilidad para pivotar tecnológicamente cuando el contexto lo exige. Cambiar a **Shiny for Python** fue una de las mejores decisiones del proyecto. Nos enseñó la importancia de la administración rigurosa de recursos: evitamos el costo de licenciamiento de Power BI, redujimos la curva de aprendizaje al mantener todo el ecosistema (ETL, EDA y Visualización) en un solo lenguaje (Python) y optimizamos los tiempos de despliegue web.
*   **Recomendación Futura:** Antes de comprometer una herramienta comercial (como Power BI) en la fase de planeación, evaluar a profundidad alternativas Open Source que se integren mejor con el stack de desarrollo.

### 2. Integración y Calidad de Datos
*   **Situación:** El manejo de la limpieza de encuestas crudas.
*   **Lección Aprendida:** La calidad del Dashboard depende enteramente de la calidad del dato de origen (Garbage In, Garbage Out). La implementación de un dataset sintético inicial de 650 registros nos permitió estresar el sistema y validar las lógicas de nuestros scripts ETL antes de salir a campo con alumnos reales.
*   **Recomendación Futura:** Siempre desarrollar entornos de prueba con datos sintéticos robustos antes de lanzar instrumentos de recolección al público.

### 3. Gestión de Stakeholders y Expectativas
*   **Situación:** Manejo de la relación entre los resultados de la encuesta y los concesionarios.
*   **Lección Aprendida:** Los datos pueden generar roces políticos. Al observar que el aumento de precios disminuía drásticamente la satisfacción de los alumnos (correlación negativa), comprendimos el alto riesgo de conflicto con los concesionarios.
*   **Recomendación Futura:** Mantener siempre el control de acceso al Dashboard. La información debe ser consumida primero por las autoridades (Patrocinador) en privado, antes de tomar cualquier acción punitiva o pública contra un concesionario.

### 4. Gobernanza y Documentación
*   **Situación:** Manejo del cronograma y múltiples documentos (Riesgos, Presupuesto, RACI).
*   **Lección Aprendida:** La estructura de gobernanza pesada es útil, pero debe ser adaptable. Organizar todo en una Estructura de Desglose del Trabajo (EDT) clara evitó cuellos de botella entre los desarrolladores y los Project Managers.
*   **Recomendación Futura:** Mantener la disciplina de documentar las decisiones (como se hizo con el cambio a Shiny) en el momento en que ocurren, no al final del proyecto.
