# Documento de Planeación del Proyecto
## Query & Coffee

**1. Objetivo General**
Desarrollar una herramienta analítica de evaluación del rendimiento y percepción de los servicios alimentarios en ESCOM, mediante la recolección de datos vía encuestas digitales y su procesamiento estadístico, con el fin de proporcionar a las autoridades institucionales información que sustente la toma de decisiones estratégicas sobre las concesiones y la mejora del bienestar estudiantil.

**2. Alcance**
El diseño, implementación y despliegue de un ecosistema de análisis de datos para evaluar el servicio de las cafeterías y barras de café dentro de la Escuela Superior de Cómputo (ESCOM). Abarca desde la creación de encuestas digitales, el proceso de extracción, transformación y carga (ETL), hasta la entrega de un dashboard interactivo que permita comparar rendimiento en términos de calidad, precio e higiene.

**3. Resumen**
Query & Coffee es una iniciativa basada en datos que busca empoderar a la administración de la escuela. Al transformar las percepciones subjetivas en Indicadores Clave de Desempeño (KPIs), el proyecto brindará argumentos cuantitativos para fundamentar acciones como la renegociación, exigencia de mejoras o revocación de los permisos a los concesionarios actuales.

**4. Supuestos**
*   **Participación Ciudadana:** La comunidad estudiantil tiene la disposición de participar activamente en el levantamiento de datos.
*   **Infraestructura Tecnológica:** Los servicios de hosting y bases de datos seleccionados mantendrán su operatividad durante el ciclo de vida del proyecto.
*   **Permisividad Institucional:** Las autoridades permitirán la colocación de material informativo (QR) en puntos estratégicos.

**5. Elementos fuera del alcance**
No se incluyen auditorías financieras a las empresas, análisis químicos de alimentos, ni la evaluación de comercios externos a la periferia oficial del plantel.

**6. Requerimientos del Negocio**
*   **Funcionales:**
    *   (RF-01) Creación y distribución de encuestas digitales vía código QR.
    *   (RF-02) Motor de base de datos para almacenar respuestas en tiempo real de forma estructurada.
    *   (RF-03) Visualizaciones comparativas entre "Cafetería Principal" y "Barras de Café".
    *   (RF-04) Filtrado de datos por segmento de usuario (alumno, administrativo).
*   **No Funcionales:**
    *   (RNF-01) Usabilidad: Interfaz intuitiva para usuarios no técnicos.
    *   (RNF-02) Disponibilidad: Formulario disponible 24 horas durante el levantamiento.
    *   (RNF-03) Escalabilidad: Base de datos capaz de soportar al menos 500 entradas.
*   **Capacitación:**
    *   (CAP-01) Manual de usuario para la interpretación de métricas en el dashboard.
    *   (CAP-02) Sesión de transferencia de conocimientos sobre mantenimiento básico de BD.
*   **Seguridad:**
    *   (SEG-01) Privacidad: Protocolos de anonimización (cumplimiento LFPDPPP).
    *   (SEG-02) Control de acceso: Edición restringida mediante credenciales de administrador.

**7. Organigrama (Actualizado)**
Se implementa una estructura jerárquica y orientada a proyectos. Se han realizado los ajustes solicitados para reflejar la dependencia superior y la integración de dos líderes de proyecto:
*   **Patrocinador / Director del Proyecto (Sponsor):** Rol superior encargado de la toma de decisiones a nivel institucional e inyección presupuestal.
    *   **Project Manager 1 (Técnico y Datos):** Roció Palacios Solano (Liderazgo en modelo de datos y ejecución técnica).
    *   **Project Manager 2 (Operaciones y Calidad):** Francisco López Carlos Uriel (Liderazgo en gestión de stakeholders, validación de encuestas y control de calidad).
        *   **Ingeniería de Datos:** Francisco López Carlos Uriel
        *   **Análisis de Datos:** Hernández Anaya Ulises
        *   **Especialista de Business Intelligence (BI):** Palma Pacheco Alan Daniel

**8. Misión, Visión y Valores**
*   **Misión:** Proveer a la comunidad politécnica herramientas de inteligencia de negocios accesibles y precisas que garanticen la transparencia y calidad en los servicios alimentarios dentro de ESCOM.
*   **Visión:** Ser el estándar de evaluación analítica para todas las concesiones dentro del Instituto Politécnico Nacional, asegurando decisiones justas basadas en evidencia.
*   **Valores:** Transparencia, Objetividad, Innovación Tecnológica, Responsabilidad Ética.

**9. Análisis de Factibilidad**
*   **Técnica:** Alta. El equipo domina las tecnologías (Python, SQL, herramientas BI) y los requerimientos computacionales se cubren con el presupuesto asignado.
*   **Económica:** Factible. El presupuesto de $60,000.00 MXN está justificado por el alto retorno de inversión administrativo al prevenir fugas de capital y mejorar el ecosistema institucional.
*   **Operativa:** Alta, siempre que se cuente con la permisividad institucional (supuesto validado) para colocar códigos QR.

**10. Matriz RACI**
Roles y responsabilidades claramente definidos entre los stakeholders del proyecto para las actividades clave. 
*(Documento ya validado y referenciado como anexo: [MATRIZ-RACI_QUERY&COFFE.xlsx](file:///c:/APTI/MATRIZ-RACI_QUERY&COFFE%20%20(1).xlsx))*

**11. EDT (Estructura de Desglose del Trabajo)**
El proyecto se divide en 5 grandes fases:
1.  **Inicio** (Problema, Objetivos, Equipo)
2.  **Planeación** (Metodología, Cronograma, Diseño de Encuestas)
3.  **Ejecución** (Aplicación, Recopilación ETL, Análisis EDA)
4.  **Monitoreo** (Validación de datos, Ajustes metodológicos)
5.  **Cierre** (Resultados finales, Reportes, Documento final)
*(Detalles consolidados en anexos: [Diagrama.pdf](file:///c:/APTI/Diagrama.pdf) y [Diccionario de EDT (1).xlsx](file:///c:/APTI/Diccionario%20de%20EDT%20.xlsx))*
