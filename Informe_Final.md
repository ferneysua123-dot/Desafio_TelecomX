# 📊 Informe de Análisis de Evasión de Clientes (Churn)
## Proyecto: TelecomX LATAM

---

## 🔹 1. Introducción

El objetivo de este análisis es comprender los factores que influyen en la **evasión de clientes (Churn)** en TelecomX LATAM. El churn ocurre cuando los clientes cancelan sus servicios, lo cual representa un problema importante para las empresas de telecomunicaciones, ya que **retener clientes suele ser más económico que adquirir nuevos**.

A través de técnicas de **análisis de datos con Python**, se busca identificar patrones y comportamientos que permitan comprender por qué los clientes abandonan el servicio y así generar **estrategias que ayuden a mejorar la retención**.

---

## 🔹 2. Limpieza y Tratamiento de Datos

Los datos fueron obtenidos desde un **archivo JSON**, el cual contenía información estructurada en diferentes secciones relacionadas con los clientes, los servicios contratados y la facturación.

Durante el proceso de preparación de datos se realizaron las siguientes acciones:

- Importación y estructuración de los datos utilizando **Pandas**.
- Normalización de las estructuras anidadas del JSON para convertirlas en un **DataFrame tabular**.
- Conversión de columnas numéricas que estaban almacenadas como texto (por ejemplo, cargos totales).
- Tratamiento de **valores faltantes**, especialmente en clientes con **0 meses de antigüedad**.
- Estandarización de variables categóricas y revisión de los tipos de datos.

Estos pasos permitieron obtener un **dataset limpio y consistente**, adecuado para el análisis exploratorio.

---

## 🔹 3. Análisis Exploratorio de Datos (EDA)

El análisis exploratorio permitió identificar patrones importantes relacionados con el churn mediante visualizaciones realizadas con **Matplotlib y Seaborn**.

Los principales hallazgos fueron:

- Aproximadamente **una cuarta parte de los clientes ha cancelado el servicio**, lo que indica una tasa de churn significativa.
- Los clientes con **menor antigüedad** presentan mayor probabilidad de abandono, especialmente durante los primeros meses.
- Los **contratos mensuales** están asociados con mayores tasas de churn en comparación con contratos de mayor duración.
- Los **métodos de pago manuales** presentan más abandono que los pagos automáticos.
- Los clientes con **cargos mensuales más altos** tienden a cancelar el servicio con mayor frecuencia.

Estos resultados muestran que existen **factores contractuales, económicos y de permanencia** que influyen directamente en el abandono de clientes.

---

## 🔹 4. Conclusiones e Insights

El análisis permitió identificar varios factores clave relacionados con la evasión de clientes:

- Los **contratos mes a mes** presentan mayor riesgo de churn.
- Los clientes con **poca antigüedad** son los más propensos a abandonar el servicio.
- Los **métodos de pago automatizados** ayudan a reducir la probabilidad de cancelación.
- Los **cargos mensuales altos** pueden afectar la percepción de valor del servicio.
- Los clientes que utilizan **servicios adicionales** tienden a permanecer más tiempo en la empresa.

Estos insights pueden ayudar a la empresa a comprender mejor el comportamiento de sus clientes y tomar decisiones basadas en datos.

---

## 🔹 5. Recomendaciones

Con base en los resultados del análisis, se proponen las siguientes estrategias:

- **Promover contratos de mayor duración** mediante descuentos o beneficios exclusivos.
- Implementar estrategias de **retención durante los primeros meses del cliente**.
- Fomentar el uso de **pagos automáticos** para reducir la fricción en el proceso de pago.
- Fortalecer los **servicios complementarios** que aumenten el valor percibido del servicio.
- Revisar la **estructura de precios** de los planes con cargos mensuales más altos.

---

## 📌 Conclusión

Este proyecto permitió aplicar un flujo completo de análisis de datos utilizando Python, incluyendo **preparación de datos, análisis exploratorio y generación de insights estratégicos**.

Los resultados muestran que comprender los factores que influyen en el churn permite a las empresas diseñar **estrategias de retención más efectivas**, mejorar la experiencia del cliente y reducir la pérdida de usuarios.
