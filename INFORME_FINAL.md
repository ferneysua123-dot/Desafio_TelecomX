# 📊 Informe de Análisis de Evasión de Clientes (Churn)  
## TelecomX LATAM

---

## 🔹 1. Introducción

El objetivo principal de este análisis es **entender los motivos por los cuales los clientes de TelecomX deciden cancelar sus servicios (Churn)**.

La **retención de clientes** es crítica en el sector de telecomunicaciones, ya que **adquirir un nuevo cliente es significativamente más costoso que mantener uno actual**.  

A través de **ciencia de datos**, buscamos identificar **patrones de comportamiento** que permitan a la empresa tomar **acciones proactivas para reducir la evasión de clientes**.

---

## 🔹 2. Limpieza y Tratamiento de Datos

Para asegurar la integridad del análisis, se realizaron transformaciones profundas en el conjunto de datos:

### 📌 Traducción y Estandarización
- Se renombraron las **21 columnas originales al español**.
- Se normalizaron los textos:
  - Eliminando espacios en blanco con `strip()`
  - Convirtiendo todos los textos a **minúsculas**
- Esto permitió **evitar duplicidad de categorías**.

### 📌 Corrección de Tipos de Datos
- La columna **Cargo_Total** fue transformada de **texto a numérico (`float`)**.
- Se gestionaron valores nulos provenientes de **clientes con 0 meses de antigüedad**.

Además, se crearon variables derivadas:

```python
Cuentas_Diarias = Cargo_Mensual / 30
