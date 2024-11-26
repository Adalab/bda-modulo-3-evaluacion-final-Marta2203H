En este ejercicio de evaluación del módulo 3, analizamos dos csv de datos proporciondos por una aerolínea para analizar el comportamiento de sus clientes de lealtad. 

Los dos csv que hemos utilizado para este análisis son:

    - Customer Flight Analysis.csv: Contiene datos sobre las actividades de vuelo de los clientes, incluyendo el número de vuelos reservados, distancia volada, puntos acumulados y redimidos ...
    - Customer Loyalty History.csv: Proporciona detalles sobre el perfil de los clientes, como ubicación, nivel educativo, ingresos, estado civil ...

**Fases del Proyecto**
**Fase 1:** Exploración y Limpieza de Datos

    1.Exploración Inicial:
    
        Realizamos una exploración inicial de los datos para identificar problemas como valores nulos, atípicos o datos faltantes.
        Utilizamos la librería Pandas para obtener información sobre la estructura de los datos y estadísticas básicas de las columnas clave.

    2. Limpieza de Datos:

      Tratamos los valores nulos en las columnas clave para asegurar que los datos estuvieran completos y listos para el análisis.
      Corregimos los datos, ajustando los tipos de datos para asegurar que la información estuviera bien estructurada.

    3. Unión de Conjuntos de Datos:

      Unimos ambos archivos usando el identificador único Loyalty Number para correlacionar la actividad de vuelo con el perfil de los clientes de manera eficiente, con un merge.

**Fase 2:** Visualización de Datos

Utilizamos gráficas de visualización para responder a las siguientes preguntas :

    Distribución de la cantidad de vuelos reservados por mes durante el año:
    
        Analizamos cómo varía el número de vuelos reservados por los clientes mes a mes a lo largo del año, con un barplot.

    Relación entre la distancia de los vuelos y los puntos acumulados:
        Analizamos la relación entre la distancia total volada y los puntos acumulados en el programa de lealtad, con un scatterplot.

    Distribución de los clientes por provincia o estado:
        Analizamos la ubicación geográfica de los clientes, visualizando su distribución por provincias o estados, con un counplot.

    Comparación del salario promedio entre diferentes niveles educativos:
        Comparamos los ingresos anuales promedio de los clientes según su nivel educativo, con un barplot.

    Proporción de clientes con diferentes tipos de tarjetas de fidelidad:
        Analizamos la distribución de los clientes según el tipo de tarjeta de lealtad que poseían, con pie.

    Distribución de los clientes según su estado civil y género:
        Visualizamos la relación entre el estado civil y el género de los clientes, con un countplot.

**Fase 3:** Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo

    Preparación de Datos:

        Filtramos los datos para incluir únicamente las columnas relevantes: 'Flights Booked' y 'Education'.
    
    Análisis Descriptivo:

        Agrupamos los datos por nivel educativo y se calcularon estadísticas descriptivas, como el promedio, la desviación estándar y los percentiles del número de vuelos reservados para cada grupo.

    Prueba Estadística:

        Sin realizar
    
**Herramientas y Librerías**

    Pandas: Para la manipulación y análisis de datos.
    Matplotlib y Seaborn: Para la visualización de datos.
    Scipy: Para realizar pruebas estadísticas, como la prueba A/B.


