# Query & Coffee
## Caso de Negocio

**Ciudad de México a 16 de febrero de 2026**

**ID:** P-01  
**Fecha de Inicio:** 09 / 02 / 2026  
**Fecha de Terminación:** 19 / 07 / 2026  

---

## ANTECEDENTE
Los problemas de calidad y accesibilidad a la comida en la Escuela Superior de Cómputo han sido objeto de discusión desde un periodo de tiempo bastante amplio. Para hablar de los antecedentes comprobables que concuerdan con las observaciones empíricas de los estudiantes, abarcaremos un periodo desde el 2022 hasta la actualidad.

En principios de 2022 las opciones de acceso a comedores y alimentos dentro de las instalaciones eran limitadas, la concentración más grande de estudiantes se ubicaba en la cafetería principal que cuenta con espacio de cocina, tienda y comedor.

A partir 2022 se han llevado a cabo reasignaciones de concesiones para nuevos comedores y barras de cafetería que ocuparían las instalaciones, los cambios más importantes fueron los de la cafetería principal y la barra de café en el edificio 5. Ambos puntos presentaban precios elevados para el presupuesto estudiantil promedio; sin embargo, el factor que detonó mayor rechazo fue el deterioro en la calidad e higiene de los productos.

La ausencia de un sistema estructurado de control y supervisión sanitaria representa un área de oportunidad institucional, particularmente en una etapa temprana de operación del servicio.

---

## JUSTIFICACIÓN DEL PROYECTO

La petición de cafeterías con precios accesibles y buena calidad es a la fecha una de las discusiones más fuertes dentro de la comunidad de alumnos de la ESCOM.

Aún teniendo un sustento para abordar este tema no contamos con una publicación de alguna investigación ni proyecto de análisis realizado que estudie y ofrezca un panorama real de la situación de este dilema para poder proponer un plan de acción, es por esto que nace la propuesta de realizar este proyecto.

Esta propuesta no solo busca analizar objetivamente las condiciones actuales, sino también generar insights estratégicos que sustenten la planeación y optimización del servicio. De este modo, se aspira a fortalecer la credibilidad de las cafeterías, promoviendo un entorno universitario basado en la confianza y el bienestar de la comunidad.

### Justificación Económica y Estudio de Mercado (NUEVO)
El desarrollo de este proyecto opera con un costo total estimado en $546,626.55 MXN (distribuido en costos operativos de personal especializado y costos tecnológicos de hardware, software y nube). Aunque el proyecto es de carácter consultivo, su retorno de inversión (ROI) es altamente justificable: una solución de este nivel solicitada a consultoras externas superaría el millón de pesos, mientras que realizarlo internamente con perfiles de ESCOM asegura viabilidad, pertinencia y ahorro institucional.

Un estudio de mercado preliminar dentro del ecosistema universitario indica que el estudiante y docente promedio realiza un gasto constante en alimentación durante su jornada académica. Si las concesiones internas no ofrecen calidad o higiene, la comunidad busca opciones externas o informales, lo que representa una fuga de capital para la economía interna de la escuela y un aumento en el riesgo de enfermedades gastrointestinales. Al contar con un *Dashboard Interactivo* y datos duros (ETL y EDA), la administración de ESCOM tendrá el poder de negociación necesario para exigir mejores condiciones, fundamentar la revocación de permisos a terceros (conforme a los artículos 267 y 281 del Reglamento Interno del IPN) si el servicio no es acorde a los aprovechamientos pagados, o atraer nuevos proveedores que se ajusten a la demanda real, asegurando así que los ingresos generados dentro del plantel se traduzcan en un servicio óptimo y seguro.

En el ámbito universitario, la evaluación de cafeterías suele abordarse desde tres ángulos principales (Participación, Dimensiones Evaluadas y Optimización Técnica). A diferencia de las encuestas institucionales tradicionales que suelen entregar reportes estáticos, este proyecto se distingue por crear un Ecosistema de Datos (ETL) y Visualización Interactiva (BI) en tiempo real.

---

## ALCANCE
El presente proyecto se enfoca en la creación de un ecosistema de datos que transforme la percepción cualitativa de la comunidad en indicadores cuantitativos de gestión. El alcance se divide en las siguientes dimensiones:

### 1. Alcance Funcional (Lo que el proyecto hará)
*   **Diseño de Instrumentos:** Creación de encuestas digitales con reactivos validados que midan: calidad del alimento, tiempo de espera, higiene percibida, atención al cliente y relación costo-beneficio.
*   **Recolección de Datos Primarios:** Levantamiento de información directamente en las instalaciones de ESCOM mediante métodos digitales.
*   **Procesamiento y Limpieza (ETL):** Tratamiento de los datos recolectados para eliminar registros duplicados, inconsistentes o malintencionados (limpieza de ruido).
*   **Análisis Comparativo:** Generación de un modelo de comparación entre los diferentes puntos de venta (Cafetería Central vs. Barras de Café) basado en los KPIs definidos.
*   **Dashboard de Visualización:** Entrega de una interfaz interactiva que permita filtrar resultados por tipo de usuario (alumno/personal).

### 2. Alcance Geográfico y Poblacional
*   **Ubicación:** Únicamente las instalaciones físicas de la Escuela Superior de Cómputo (ESCOM).
*   **Puntos de Venta:** Cafetería central, barra de café del Edificio 5 y cualquier otro concesionario formal dentro del plantel.
*   **Sujetos de Estudio:** Alumnos con matrícula vigente, docentes y personal administrativo activo.

### 3. Alcance Tecnológico
*   Implementación de una base de datos para el almacenamiento de las respuestas.
*   Uso de herramientas de análisis estadístico y visualización para la interpretación de resultados.

### 4. Exclusiones
Para garantizar la viabilidad del proyecto en el tiempo establecido, no se incluirá:
*   Análisis de puestos de comida ambulante o locales externos a la periferia de la escuela.
*   Auditorías contables o financieras internas de las empresas concesionarias.
*   Intervención directa en la gestión de las cafeterías (el proyecto es informativo y consultivo, no ejecutivo).
*   Análisis de laboratorios químicos de los alimentos (la evaluación de higiene es percibida, no microbiológica).

### 5. Consideraciones Éticas y de Privacidad
*   **Anonimato:** El sistema no recolectará datos personales sensibles (nombres, correos personales o números de boleta) que permitan identificar a los participantes, cumpliendo con la normativa de protección de datos personales.

---

## OBJETIVOS

**Objetivo General:** Desarrollar una herramienta analítica de evaluación del rendimiento y percepción de los servicios alimentarios en ESCOM, mediante la recolección de datos vía encuestas digitales y su procesamiento estadístico, con el fin de proporcionar a las autoridades institucionales información que sustente la toma de decisiones estratégicas sobre las concesiones y la mejora del bienestar estudiantil.

**Objetivos Específicos:**
*   Diseñar y validar un instrumento de recolección de datos especializado en servicios de cafetería, a través de la definición de indicadores clave (calidad, precio, higiene) y pruebas piloto.
*   Ejecutar el levantamiento de información en la población de ESCOM, mediante la difusión estratégica de códigos QR y formularios digitales.
*   Analizar la correlación entre las variables de costo, calidad y satisfacción del usuario, utilizando técnicas de análisis estadístico y limpieza de datos (ETL).
*   Implementar un dashboard interactivo de visualización de datos, integrando los resultados analizados en una plataforma de Business Intelligence.

---

## ANÁLISIS DE RIESGOS DEL PROYECTO

1.  **Riesgo de Subrepresentación de la Muestra**
    *   *Descripción:* Existe la posibilidad de que la participación no alcance el volumen necesario para ser estadísticamente significativa.
    *   *Impacto:* Los KPIs carecerán de validez.
2.  **Riesgo de Integridad y "Ruido" en los Datos Recolectados**
    *   *Descripción:* Sistema vulnerable al ingreso de registros duplicados o "spam".
    *   *Impacto:* El proceso ETL podría verse desbordado, sesgando el análisis exploratorio (EDA).
3.  **Vulnerabilidad por Dependencia de Infraestructura Crítica**
    *   *Descripción:* Concentración de la inversión en tres equipos de cómputo, sin recursos de respaldo.
    *   *Impacto:* Fallas técnicas comprometerían de inmediato la capacidad operativa en la fase de ejecución.
4.  **Riesgo de Compromiso de la Privacidad y Anonimato**
    *   *Descripción:* Un error en el diseño podría capturar accidentalmente metadatos o información identificable.
    *   *Impacto:* Rechazo del proyecto por la comunidad e invalidación institucional.
5.  **Cuello de Botella en la Ruta Crítica (Fase Técnica Final)**
    *   *Descripción:* Alta dependencia secuencial y tiempos muy ajustados (Desarrollo del Dashboard en solo 3 días).
    *   *Impacto:* Retrasos acumulados generarían efecto dominó impidiendo el cierre a tiempo.

---

## BENEFICIOS
*   **Optimización del servicio:** Genera insights estratégicos que permiten mejorar la planeación y calidad.
*   **Bienestar de la comunidad:** Promueve un entorno basado en la confianza y satisfacción.
*   **Transparencia institucional:** Transforma la percepción subjetiva en indicadores cuantitativos.
*   **Identificación de puntos críticos:** Detecta factores de rechazo para corregirlos puntualmente.

---

## PERSONAL INVOLUCRADO (ACTUALIZADO CON CONTACTOS)

*   **Administrador del Proyecto (1 persona):** Francisco López Carlos Uriel.
    *   *Perfil:* Coordinador líder responsable de la planeación, seguimiento del cronograma y entrega final.
    *   *Contacto:* francisco.lopez.cu@escom.ipn.mx | Tel: 55-1234-5678 (Dato de prueba)

*   **Analistas de Datos / Desarrolladores (2 personas):** 
    *   **Hernández Anaya Ulises**
        *   *Perfil:* Especialista técnico encargado del diseño de instrumentos, procesos de limpieza de datos (ETL), análisis estadístico y desarrollo del Dashboard interactivo.
        *   *Contacto:* ulises.hernandeza@escom.ipn.mx | Tel: 55-8765-4321 (Dato de prueba)
    *   **Palma Pacheco Alan Daniel**
        *   *Perfil:* Especialista técnico encargado del diseño de instrumentos, procesos de limpieza de datos (ETL), análisis estadístico y desarrollo del Dashboard interactivo.
        *   *Contacto:* alan.palmap@escom.ipn.mx | Tel: 55-1122-3344 (Dato de prueba)

---

## TIPO DE CONTRATACIÓN Y RECURSOS
*   **Tipo de contratación:** Interna / Proyecto Institucional (Asignación interna por proyecto).
*   **Presupuesto Total:** $546,626.55 MXN (Costos Operativos y Tecnológicos).

---

## GLOSARIO TÉCNICO

| Término | Definición |
| :--- | :--- |
| **BI (Business Intelligence)** | Conjunto de estrategias y herramientas enfocadas en la administración de datos para permitir una comparación ágil del rendimiento. |
| **Dashboard** | Interfaz interactiva que permite filtrar resultados y visualizar indicadores cuantitativos de gestión. |
| **EDA** | Exploratory Data Analysis; procesamiento estadístico exploratorio utilizado para analizar variables de costo, calidad y satisfacción. |
| **ETL** | Proceso técnico de extracción, limpieza y transformación de datos para eliminar registros duplicados o malintencionados. |
| **Instrumentos de recolección** | Diseño de encuestas digitales con reactivos validados. |
| **KPI (Key Performance Indicator)**| Indicadores clave de desempeño definidos para transformar la percepción cualitativa en métricas cuantitativas. |
| **Muestra Representativa** | Volumen de participación necesario para que los resultados sean estadísticamente significativos. |
| **Ruta Crítica** | Cronograma con dependencia secuencial de tareas donde cualquier retraso compromete la fecha de cierre. |
