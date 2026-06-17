# Fase de Diseño del Proyecto
## Proyecto: Query & Coffee

Esta fase documenta la creación del producto de software final. Es importante destacar que, durante la ejecución de esta fase, se tomó una **decisión arquitectónica crítica**: se descartó el uso planificado de Power BI y se optó por desarrollar el Dashboard utilizando **Shiny for Python**. 

Esta decisión se fundamentó en las siguientes ventajas operativas y financieras:
*   **Costos y Mantenimiento:** El desarrollo con Shiny for Python es completamente gratuito (Open Source), eliminando la necesidad de adquirir licencias costosas de Power BI.
*   **Integración Nativa:** Al estar programado en Python, permite conectarse de forma nativa e ininterrumpida con los scripts previos de ETL (Extracción, Transformación y Limpieza) y EDA (Análisis Exploratorio de Datos), los cuales también utilizan librerías de Python (Pandas).
*   **Despliegue Web:** Facilita el empaquetado y despliegue del Dashboard como una aplicación web pura, facilitando el acceso a los *stakeholders* desde cualquier navegador.

### 1. Levantamiento del Dataset
Para alimentar y probar el sistema, se construyó un dataset sintético mediante un script en Python (`generar_dataset.py`). El archivo resultante (`dataset_encuestas_cafeterias_escom.csv`) concentra **650 registros** de encuestas sobre los tres concesionarios de alimentos de ESCOM: Cafetería Principal, Barra de Café 1 y Barra de Café 2. 
Este volumen supera el requerimiento no funcional RNF-03 (500 registros mínimos) y no contiene información personal identificable, cumpliendo con los estándares de seguridad (SEG-01) y la LFPDPPP.

### 2. Desarrollo en Código del Dashboard
El tablero interactivo fue implementado utilizando `pandas` para el procesamiento y `matplotlib` para la generación de gráficas estadísticas. El archivo principal `app.py` está organizado en tres bloques:
1.  **Carga y preprocesamiento:** Lectura del CSV, conversión de fechas y extracción de catálogos para filtros.
2.  **Interfaz de Usuario (UI):** Barra lateral con filtros reactivos (segmento, concesionario, producto, fechas), indicadores clave y sección de hallazgos ejecutivos automáticos.
3.  **Lógica del Servidor (Server):** Función reactiva `datos_filtrados()` que asegura la consistencia de todos los gráficos al momento de usar los filtros.

### 3. Visualización y Análisis de Resultados
El tablero presenta los resultados a través de cinco componentes visuales clave:
*   **KPIs Generales:** Total de encuestas, ticket promedio, satisfacción general (sobre 5 estrellas) y variación porcentual de precios.
*   **Hallazgos Automáticos:** Señala al concesionario con mejor calidad percibida, menor higiene y mayor ajuste de precios.
*   **Tendencia Semanal de Precios:** Gráfica de líneas que muestra la evolución del ticket promedio por concesionario.
*   **Comparativa de Indicadores:** Gráfica de barras que contrasta calidad e higiene entre la Cafetería Principal y las Barras de Café.
*   **Dispersión Precio-Satisfacción:** Evalúa la correlación entre lo que paga el alumno y qué tan satisfecho resulta.

Los resultados preliminares muestran que tras un aumento simulado de precios en abril, la percepción en la Cafetería Principal disminuyó notablemente, demostrando una correlación débil y negativa (el incremento en costo no se tradujo en mejor servicio).

---
*(Nota: Insertar en este espacio las capturas de pantalla o imágenes correspondientes a las Figuras 1, 2 y 3 del Dashboard funcionando).*
