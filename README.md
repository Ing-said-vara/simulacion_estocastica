# Tarea 2: Simulación MCMC de tiempos de resolución de incidencias de soporte TI

Notebook elaborado en Python / Google Colab para la asignatura **Simulación Estocástica**.

## Objetivo

Estimar el tiempo promedio de resolución de una incidencia mediante el algoritmo Metropolis–Hastings, con cuatro cadenas MCMC, diagnóstico de convergencia y análisis de resultados.

## Archivos

- `Tarea_2_MCMC_Soporte_TI.ipynb`: desarrollo del ejercicio, código, tablas y gráficas.

## Datos

Se utilizaron **40 observaciones simuladas** de una distribución exponencial con promedio teórico de 25 minutos. No son datos recolectados de una empresa.

## Reproducibilidad

Abrir el notebook en Google Colab y seleccionar **Entorno de ejecución > Ejecutar todas**. Se recomienda un entorno Python 3 con `numpy`, `pandas`, `matplotlib`, `scipy` y `arviz`. Si ArviZ no está instalado, ejecutar `!pip install arviz`. La semilla inicial es 42.

## Autor

Ing. Pedro Said Vara Chacón — Maestría en Estadística Aplicada.
