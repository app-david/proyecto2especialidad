# Análisis de Deserción de Clientes de Telecomunicaciones

Este proyecto analiza un conjunto de datos de clientes de telecomunicaciones para identificar los factores que impulsan la deserción.

**Objetivo:** Comprender las causas de la deserción y generar estrategias para reducirla.

**Metodología:**

1. **Exploración y limpieza de datos:** Se carga y explora el conjunto de datos `telecom_churn.csv`, verificando su estructura, tipos de datos y valores faltantes.
2. **Análisis de churn:** Se calcula la tasa de deserción general y se analiza su relación con variables como:
    * Plan internacional
    * Buzón de voz
    * Duración de la cuenta
    * Uso del servicio (minutos diurnos, nocturnos, total de llamadas)
    * Llamadas al servicio al cliente
    * Costo de llamadas (diurnas, nocturnas, internacionales)
3. **Análisis comparativo de costos:** Se compara el costo total de las llamadas diurnas, nocturnas e internacionales entre clientes con y sin deserción (churn).
4. **Visualización de resultados:** Se utilizan gráficos para visualizar las relaciones entre las variables y la deserción.

**Resultados:**

Se identifican los factores que tienen mayor impacto en la deserción, como la cantidad de llamadas al servicio al cliente, el costo de las llamadas y la presencia de un plan internacional. Se presentan conclusiones y recomendaciones para la empresa.

**Herramientas:**

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

**Instrucciones:**

1. Abre el archivo `[nombre_del_notebook].ipynb` en Google Colab.
2. Ejecuta todas las celdas del notebook para realizar el análisis.
3. Revisa los resultados y las visualizaciones generadas.

**Licencia:**

Este proyecto está bajo la **MIT License**. Ver el archivo `LICENSE` para más detalles.

**Autores:**

David Gutiérrez (Cédula: 1019034574)

**Fecha:**

[Fecha de creación del proyecto]
