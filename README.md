# Identificación de Operadores Ineficaces en un Sistema de Telefonía.

Una empresa de telecomunicaciones necesitaba evaluar el desempeño de los operadores de su centro de llamadas para detectar ineficiencias que afectaban la calidad del servicio. Se observaban problemas relacionados con llamadas perdidas, tiempos de espera elevados y diferencias significativas en el rendimiento entre operadores. La organización requería un análisis basado en datos para identificar operadores con bajo desempeño y generar recomendaciones que permitieran optimizar la operación del servicio.

Desarrollé un análisis integral de datos que permitió identificar operadores ineficaces mediante la definición de métricas de desempeño, el análisis estadístico y la validación de hipótesis. El proyecto incluye la preparación y limpieza de datos, la construcción de indicadores clave, la detección de operadores con bajo rendimiento y la generación de recomendaciones orientadas a mejorar la eficiencia operativa.

# Herraminetas y tecnologías.

- Excel: Archivo CSV
- Librerías de Python (pandas, numpy, matplotlib, seaborn, scipy)
- Limpieza de datos
- Manipulación de datos
- Visualización de datos
- Pruebas de hipótesis.

# Metodologías y análisis.

Inicié el proyecto comprendiendo los objetivos del negocio y definiendo qué características determinaban a un operador ineficaz. Para ello, se establecieron criterios relacionados con una alta tasa de llamadas perdidas, tiempos de espera elevados, bajo volumen de llamadas salientes y métricas complementarias como la duración promedio de las llamadas.

Posteriormente, cargué los conjuntos de datos de telecomunicaciones y clientes, verificando la estructura de las variables, la calidad de los registros y la existencia de duplicados. realicé un proceso de limpieza que incluyó el tratamiento de valores nulos, la eliminación de registros inconsistentes y la conversión de tipos de datos a formatos adecuados. Además, hice una variable derivada para calcular el tiempo de espera de cada llamada.

Con los datos preparados, desarrollé un análisis exploratorio para comprender el comportamiento general del sistema. Analicé distribuciones de llamadas entrantes y salientes, llamadas internas y externas, duración de llamadas, volumen de actividad por cliente y tendencias temporales. Esto para facilitar la interpretación de los resultados se utilizaron histogramas, diagramas de caja y gráficos de series temporales.

Construí indicadores de desempeño por operador, incluyendo la tasa de llamadas perdidas, el tiempo promedio de espera, el número de llamadas salientes y la duración promedio de las llamadas. Estas métricas permitieron establecer una base objetiva para evaluar el rendimiento individual.

La identificación de operadores ineficaces se realizó mediante tres enfoques complementarios: 
- Definición de umbrales utilizando percentiles
- Comparación contra promedios generales
- Detección de valores atípicos mediante técnicas estadísticas como IQR, Z-score y boxplots.

Para validar los hallazgos, apliqué pruebas de hipótesis estadísticas. Se evaluó si los operadores ineficaces presentaban tiempos de espera significativamente mayores, si las llamadas internas tenían menor duración que las externas y si existía una relación entre el volumen de llamadas atendidas y la tasa de llamadas perdidas. Asi mismo, incorporé un análisis por plan tarifario mediante la integración de los datos de clientes para determinar si el tipo de plan influía en el desempeño operativo.

# Resultados y conclusiones.

Los resultados facilitaron la generación de recomendaciones enfocadas en la redistribución de la carga de trabajo, la capacitación de operadores con bajo desempeño y la optimización de los procesos de atención. Gracias a este enfoque basado en datos, la organización obtuvo información accionable para mejorar la eficiencia operativa, reducir los tiempos de espera y elevar la calidad del servicio ofrecido a los clientes.

El análisis permitió identificar de manera objetiva a los operadores con menor desempeño mediante indicadores cuantificables y pruebas estadísticas que respaldaron los hallazgos. Se detectaron patrones asociados a altos tiempos de espera y elevadas tasas de llamadas perdidas, así como diferencias de rendimiento entre grupos de operadores y planes tarifarios.

Finalmente, se desarrollaron visualizaciones ejecutivas que incluyeron rankings de operadores, distribuciones de tasas de llamadas perdidas, identificación de operadores críticos y comparaciones entre clientes.
