# Análisis de Rendimiento de Tiendas - Challenge Alura Latam

## Descripción del Proyecto
Este proyecto tiene como objetivo analizar el rendimiento de cuatro tiendas (`Tienda 1`, `Tienda 2`, `Tienda 3`, `Tienda 4`) basándose en diversas métricas clave. El análisis busca identificar la tienda menos eficiente, proporcionando una base sólida para la toma de decisiones, como la desinversión. Las métricas consideradas incluyen:

*   **Ingresos Totales:** Facturación de cada tienda.
*   **Ventas por Categoría:** Cantidad de productos vendidos por categoría en cada tienda.
*   **Calificación Promedio:** Satisfacción del cliente a través de la calificación promedio de las ventas.
*   **Productos Más y Menos Vendidos:** Identificación de los productos con mayor y menor impacto en las ventas.
*   **Costo de Envío Promedio:** Eficiencia logística y costos asociados a los envíos.

El informe final concluye con una recomendación sobre cuál tienda sería la más adecuada para vender, basándose en un análisis integral de estas métricas.

## Estructura del Proyecto
El proyecto se encuentra en un notebook de Google Colab y está dividido en las siguientes secciones:

1.  **Importación de datos:** Carga los conjuntos de datos de las cuatro tiendas desde GitHub.
2.  **Análisis de facturación:** Calcula los ingresos totales por tienda.
3.  **Ventas por categoría:** Analiza la cantidad de ventas por categoría de producto en cada tienda.
4.  **Calificación promedio de la tienda:** Determina la calificación promedio de los clientes para cada tienda.
5.  **Productos más y menos vendidos:** Identifica los 3 productos más vendidos y los 3 menos vendidos por tienda.
6.  **Envío promedio por tienda:** Calcula el costo de envío promedio por tienda.
7.  **Gráficos:** Visualiza las métricas clave (total de ventas, calificación promedio, envío promedio) para una mejor comprensión.
8.  **Informe Final:** Un resumen ejecutivo con conclusiones y la recomendación final.

## Instalación
Este proyecto está diseñado para ejecutarse en Google Colab. No se requiere una instalación local compleja. Si deseas ejecutarlo en tu máquina local, necesitarás tener Python instalado.

### Requisitos previos:
*   Python 3.x
*   pip (gestor de paquetes de Python)

## Dependencias
Las principales bibliotecas de Python utilizadas en este proyecto son:

*   `pandas`: Para la manipulación y análisis de datos.
*   `matplotlib`: Para la creación de gráficos y visualizaciones.

Estas librerías suelen venir preinstaladas en Google Colab. Si las ejecutas localmente y obtienes un error de `ModuleNotFoundError`, puedes instalarlas usando pip:

```bash
pip install pandas matplotlib
```

## Cómo Ejecutar el Proyecto

### En Google Colab (Recomendado):
1.  Abre el archivo del notebook (`.ipynb`) en Google Colab.
2.  Ejecuta todas las celdas en orden. Puedes hacerlo yendo a `Entorno de ejecución > Ejecutar todas`.
3.  El notebook procesará los datos, generará los análisis y mostrará las visualizaciones y el informe final directamente en las celdas de salida.

### En entorno local (Jupyter Notebook/Lab):
1.  Abre el notebook (`.ipynb`) con Jupyter Notebook o JupyterLab.
2.  Asegúrate de que todas las dependencias estén instaladas en tu entorno virtual (ver sección de Instalación).
3.  Ejecuta cada celda del notebook secuencialmente para replicar el análisis.

## Posibles Problemas y Soluciones

### 1. Error de carga de datos (`FileNotFoundError` o URL inaccesible)
*   **Problema:** Los enlaces a los archivos CSV (`url`, `url2`, etc.) podrían cambiar o volverse inaccesibles.
*   **Solución:** Verifica que las URLs en la celda de importación de datos sean correctas y estén activas. Si los archivos se han movido, actualiza las URLs con las nuevas ubicaciones o descarga los archivos y cárgalos localmente.

### 2. `ModuleNotFoundError`
*   **Problema:** Una o más librerías requeridas no están instaladas.
*   **Solución:** Instala las librerías faltantes usando `pip install <nombre_de_la_libreria>` (e.g., `pip install pandas matplotlib`). En Colab, esto rara vez es un problema.

### 3. Problemas de visualización (gráficos no se muestran o tienen errores)
*   **Problema:** Puede haber un problema con la configuración de Matplotlib o un error en los datos que impide la correcta generación de los gráficos.
*   **Solución:** Asegúrate de que no haya errores en las celdas anteriores que afecten los DataFrames utilizados para los gráficos. Revisa la consola de salida para mensajes de error específicos de Matplotlib.

Si encuentras algún otro problema, no dudes en revisar las celdas de código y la documentación de las librerías utilizadas (Pandas, Matplotlib) para depurar el inconveniente.

```
