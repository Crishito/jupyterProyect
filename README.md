# jupyterProyect
Proyecto en Jupyter Notebook para entrega académica.

# Proyecto: Análisis de Consumo de Energía en Viviendas

## 1. Descripción
Este proyecto analiza el consumo de energía eléctrica en diferentes tipos de viviendas utilizando Python y Jupyter Notebook.  
Se calculan medidas de tendencia central, dispersión y se generan visualizaciones para interpretar los datos.

## 2. Contenido del Repositorio
- `analisis_energia.ipynb`: Notebook con todo el análisis y gráficos.
- `consumo_viviendas.csv`: Dataset utilizado.
- `plots/`: Carpeta donde se guardan los gráficos generados automáticamente.

## 3. Resultados
- Media, Mediana, Moda del consumo de energía.
- Varianza, Desviación Estándar y Rango.
- Histograma de consumo de energía (Generado con plotnine / ggplot).
- Gráfico circular de tipos de vivienda.
- Diagrama de Pareto del consumo por tipo de vivienda.

## 4. Interpretación
- La media y mediana muestran el consumo promedio y central.
- La desviación estándar indica la dispersión de los consumos respecto a la media.
- El histograma evidencia que la mayoría de viviendas tienen consumo bajo-moderado.
- El gráfico circular muestra que los departamentos son el tipo más frecuente.
- El Pareto indica que algunas viviendas (casas) concentran la mayor parte del consumo, siguiendo el principio 80/20.

## 5. Uso
1. Clonar el repositorio.
2. Abrir `analisis_energia.ipynb` en Jupyter Notebook o PyCharm.
3. Ejecutar todas las celdas para ver los resultados.
4. Los gráficos se guardan automáticamente en la carpeta `plots/`.

## Nota Importante sobre Visualización (ggplot) en PyCharm
- Este proyecto utiliza la librería plotnine (basada en la sintaxis ggplot de R) para la generación de gráficos como el Histograma.
- En Jupyter Notebook: Los gráficos se mostrarán automáticamente debajo de la celda de código.
- En PyCharm/Scripts: Debido a conflictos con el backend de Matplotlib, los gráficos de plotnine no se abrirán en una ventana emergente. La única forma de visualizarlos es abriendo directamente el archivo PNG generado:
- Verifique la carpeta plots/ después de la ejecución. El archivo histograma_frecuencia_consumo_ggplot.png contiene la visualización final en alta resolución.


## Enlace al Repositorio

El código completo y la documentación del proyecto están disponibles en GitHub:  
[Acceder al Repositorio](https://github.com/Crishito/jupyterProyect.git)