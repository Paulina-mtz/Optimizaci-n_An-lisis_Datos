# PISA - Modelo Markov

Esta carpeta contiene los códigos y archivos del proyecto **'Proceso Estocástico para Modelar el Comportamiento de los Clientes en PiSA'**, desarrollado para la empresa PiSA Medicom. 

### 📦 **Contenido:**
- `data/`: Dataset utilizado para el análisis estocástico de clientes y materiales.
- `notebooks/`: Notebooks de Jupyter con el código implementado para la modelación con Cadenas de Markov.
- `models/`: Modelos entrenados en formatos `.pkl` o `.h5`.
- `reports/`: Informe de resultados y visualizaciones generadas.
- `LICENSE`: Licencia del proyecto (CC BY-NC-ND 4.0).

### 📊 **Descripción del Proyecto:**
En este proyecto, se implementó un modelo de **Cadenas de Markov** para analizar los patrones de compra, desactivación y reactivación de los clientes y materiales distribuidos por PiSA Medicom. La metodología incluyó:

- **Matriz de Transición:** Cálculo de probabilidades de transición entre estados Activo (A) e Inactivo (I).
- **Distribución Estacionaria:** Identificación del estado a largo plazo de cada cliente y material.
- **Tiempo Medio de Recurrencia:** Estimación del tiempo esperado entre compras para clientes recurrentes.
- **Sistema de Recomendaciones:** Implementación de un sistema basado en la similitud del coseno y matrices de co-ocurrencia.

### ✅ **Objetivo del Proyecto:**
El objetivo fue optimizar la gestión de inventarios y la relación con los clientes mediante la identificación de patrones de comportamiento. Esto permitió a PiSA crear estrategias basadas en datos para retener clientes valiosos y optimizar la distribución de materiales.
