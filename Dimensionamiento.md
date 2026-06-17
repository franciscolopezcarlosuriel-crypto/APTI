# Reglas de Dimensionamiento (Project Sizing)
## Proyecto: Query & Coffee

El dimensionamiento del proyecto es una práctica fundamental de la gobernanza de TI, cuyo objetivo es evaluar de manera objetiva el esfuerzo, riesgo e impacto organizativo de una iniciativa. Esto permite asignar recursos y metodologías de gestión adecuadas.

Para sustentar matemáticamente este cálculo y transparentar los criterios, se utiliza como base el archivo **[Dimensionamiento.xlsx](file:///c:/APTI/Dimensionamiento.xlsx)**, el cual contiene la matriz de evaluación formal y las ponderaciones.

### 1. Métrica y Lógica de Clasificación Acordada

El sistema de "Query & Coffee" utiliza un **Modelo Sumatorio de Puntos** basado en la evaluación de diversas variables de esfuerzo, riesgo e impacto organizativo. A diferencia de modelos tradicionales que promedian resultados, esta metodología suma los puntos totales obtenidos.

**Definición de la Escala de Valoración (1 al 5)**
Para estandarizar cómo se califican las variables y evitar subjetividades, se utiliza la siguiente métrica general:
*   **Nivel 1 (Muy Bajo):** Esfuerzo marginal o rutina. Impacto mínimo, estrictamente localizado y aislado. Riesgo prácticamente nulo.
*   **Nivel 2 (Bajo):** Esfuerzo manejable. Requiere coordinación básica de recursos. Impacto y riesgos controlables dentro del flujo de trabajo habitual.
*   **Nivel 3 (Medio):** Esfuerzo moderado. Requiere planeación formal, métricas de calidad y afecta transversalmente a múltiples departamentos operativos (ej. alumnos, docentes y administración).
*   **Nivel 4 (Alto):** Alto nivel de esfuerzo y criticidad. Involucra partes externas o alta dirección. Riesgo considerable que exige planes de mitigación robustos y supervisión continua.
*   **Nivel 5 (Crítico):** Máximo esfuerzo y consumo de recursos críticos. Impacto sistémico, legal, normativo o comercial que, de fallar, compromete la continuidad operativa o reputación institucional a gran escala.

**Clasificación Final (Bloques de 9 puntos)**
La suma de los valores definirá el tamaño del proyecto:
*   **0 puntos:** Sin evaluar
*   **1 a 9 puntos:** Mini
*   **10 a 18 puntos:** Pequeño
*   **19 a 27 puntos:** Mediano
*   **28+ puntos:** Grande

---

### 2. Evaluación de Categorías para "Query & Coffee"

Con base en la estructura final aprobada y el contexto del proyecto, se asignan los siguientes valores para cada variable:

| Variable Evaluada | Valor Asignado | Justificación para Query & Coffee |
| :--- | :---: | :--- |
| **1. Número de personas involucradas** | **2** | Se considera la estructura organizativa final aprobada: 1 Patrocinador, 2 Project Managers paralelos, 1 Ingeniero de Datos, 1 Analista de Datos y 1 Especialista BI. Aunque el equipo no excede las 10 personas, la diversidad de roles especializados (6 personas / 5 perfiles) exige mayor coordinación, subiendo a nivel 2. |
| **2. Presupuesto** | **3** | La inversión total estimada asciende a $546,626.55 MXN (costos operativos y tecnológicos). Dentro del ecosistema escolar, esto representa un recurso económico considerable que exige seguimiento y justificación de nivel 3. |
| **3. Duración** | **2** | El proyecto tiene una duración acotada a aproximadamente 5 meses (febrero a julio de 2026), clasificándose como de corto a mediano plazo. |
| **4. Recursos de la organización** | **1** | Se requerirán recursos físicos mínimos de la escuela (solo permiso para pegar códigos QR) y uso primario de software libre/educativo y el propio equipo del proyecto. |
| **5. Procesos tecnológicos / de negocio** | **3** | Implica un nivel medio de transformación tecnológica, ya que se desarrollarán pipelines de datos (ETL) y Dashboards interactivos BI que actualmente no existen para esta gestión. |
| **6. Impacto en las operaciones** | **3** | Altera el proceso administrativo actual. DOTA a la dirección del CICS UST/ESCOM de un flujo continuo de métricas cuantificables, cambiando la forma en que evalúan el servicio. |
| **7. Impacto en socios** | **4** | Nivel Alto. Afecta directamente, y de manera pública, a las empresas concesionarias y sus contratos, basándose en la evaluación de una población de ~3,000 usuarios. |
| **8. Importancia estratégica** | **4** | Nivel Alto. El proyecto defiende el prestigio del IPN, atiende preocupaciones críticas de salud estudiantil (higiene) y evita posibles huelgas o protestas por altos precios. |
| **9. Dependencias interrelacionadas** | **2** | Aunque es independiente de otros sistemas informáticos del IPN, existe una dependencia social crítica en lograr la participación voluntaria de los estudiantes para las encuestas. |

---

### 3. Resultado Final del Dimensionamiento

Al realizar la suma de las 9 variables evaluadas bajo la escala especificada:
2 + 3 + 2 + 1 + 3 + 3 + 4 + 4 + 2 = **24 puntos totales**.

**Clasificación Final: Proyecto MEDIANO.**

*Conclusión:* El proyecto se consolida en el bloque de **19 a 27 puntos**. Si bien el proyecto es contenido en cuanto a presupuesto y tiempo, su sensibilidad política y estratégica con los proveedores externos, así como la gobernanza del equipo de roles especializados, lo establecen firmemente como un proyecto mediano que requiere un control formal.
