# Desafio_TelecomX
Analisis de evación de clientes
# 📊 Análisis de Evasión de Clientes (Churn) - TelecomX LATAM

## 📝 Descripción del Proyecto
Este proyecto tiene como objetivo identificar y comprender los factores que impulsan la pérdida de clientes (**Churn**) en la empresa **TelecomX LATAM**. Utilizando técnicas de análisis de datos con Python, el estudio busca transformar datos crudos en estrategias accionables para mejorar la retención y reducir el impacto económico que genera la cancelación de servicios.

---

## 🛠️ Tecnologías y Herramientas
*   **Lenguaje:** Python 3.x
*   **Librerías principales:** 
    *   `Pandas`: Para la limpieza, normalización y manipulación de datos.
    *   `Matplotlib` & `Seaborn`: Para la creación de visualizaciones y análisis estadístico gráfico.
*   **Fuente de Datos:** Archivo JSON con estructuras anidadas.

---

## 🚀 Proceso de Análisis

### 1. Limpieza y Tratamiento de Datos
El dataset inicial requirió un proceso exhaustivo de curación:
*   **Normalización:** Conversión de estructuras JSON anidadas a DataFrames tabulares.
*   **Corrección de Tipos:** Transformación de columnas numéricas almacenadas como texto (ej. Cargos Totales).
*   **Manejo de Valores Faltantes:** Tratamiento de nulos en clientes con antigüedad cero.
*   **Estandarización:** Limpieza de variables categóricas para asegurar consistencia en el análisis.

### 2. Hallazgos del Análisis Exploratorio (EDA)
A través de la visualización de datos, se identificaron los siguientes patrones:
*   **Tasa de Abandono:** Un 25% de la base de clientes ha cancelado el servicio.
*   **Factor Antigüedad:** Los clientes en sus primeros meses de contrato son los más propensos a irse.
*   **Tipo de Contrato:** Los contratos mensuales (mes a mes) tienen un riesgo de churn significativamente mayor que los contratos a largo plazo.
*   **Métodos de Pago:** El pago manual genera mayor fricción y abandono comparado con el pago automático.
*   **Costo:** Existe una correlación positiva entre cargos mensuales altos y la probabilidad de churn.

---

## 💡 Insights Clave
*   Los **contratos a corto plazo** son el principal predictor de evasión.
*   La adopción de **servicios adicionales** incrementa la lealtad del cliente.
*   La **automatización del pago** es una barrera efectiva contra la cancelación por olvido o fricción.

---

## 📋 Recomendaciones Estratégicas
1.  **Migración de Contratos:** Ofrecer beneficios exclusivos para mover a clientes de planes mensuales a anuales.
2.  **Plan de Bienvenida:** Reforzar la atención al cliente durante los primeros 3 a 6 meses de vida del usuario.
3.  **Incentivos Digitales:** Promover el uso de métodos de pago automáticos mediante descuentos.
4.  **Valor Agregado:** Crear paquetes que incluyan servicios complementarios para aumentar el valor percibido.

---

## 📁 Estructura del Repositorio
*   `data/`: Contiene el archivo JSON original.
*   `notebooks/`: Jupyter Notebook con el código completo (Limpieza + EDA).
*   `reports/`: Resumen ejecutivo y visualizaciones clave.

---
**Desarrollado como parte del proyecto de análisis de datos para TelecomX LATAM.**
