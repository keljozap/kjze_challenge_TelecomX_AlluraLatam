# 📊 TelecomX - Análisis de Churn

Este repositorio contiene un análisis exhaustivo sobre la evasión de clientes (Churn) en **TelecomX**, una empresa de telecomunicaciones.

## 🎯 Objetivo del Proyecto
Identificar patrones y factores clave que influyen en la decisión de los clientes de cancelar sus servicios, y proponer estrategias basadas en datos para mejorar la retención.

## 📁 Estructura del Proyecto
*   `TelecomX_LATAM.ipynb`: Notebook principal con todo el código de extracción, limpieza, análisis y visualización.
*   `TelecomX_Data.json`: (Fuente de datos) Dataset original en formato JSON anidado.

## 🛠️ Tecnologías Utilizadas
*   **Python 3.9+**
*   **Pandas:** Manipulación y limpieza de datos (incluyendo `json_normalize`).
*   **Matplotlib & Seaborn:** Visualización de datos y generación de gráficos.

## 🔍 Pasos Realizados
1.  **Extracción Interactiva:** Carga directa de datos desde repositorio remoto.
2.  **Transformación y Limpieza:**
    *   Aplanamiento de estructuras JSON anidadas.
    *   Conversión de tipos de datos (`account.Charges.Total` a numérico).
    *   Estandarización de variables categóricas.
3.  **Feature Engineering:** Creación de métricas de valor diario (`Cuentas_Diarias`).
4.  **Análisis Exploratorio (EDA):** Detección de patrones en contratos, métodos de pago y servicios.

## 🚀 Cómo Ejecutar
1. Clonar este repositorio.
2. Instalar las dependencias necesarias:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Abrir el archivo `TelecomX_LATAM.ipynb` en Jupyter Notebook, Google Colab o VS Code.
4. Ejecutar todas las celdas secuencialmente.

## 💡 Principales Conclusiones
*   Los contratos **mensuales** son el principal factor de riesgo.
*   Los usuarios con **Fibra Óptica** presentan mayor tasa de abandono.
*   El método de pago **Electronic Check** está fuertemente correlacionado con el Churn.

---
*Desarrollado para el Challenge de Data Science LATAM.*
