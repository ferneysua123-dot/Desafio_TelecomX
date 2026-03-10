📊 Informe de Análisis de Evasión de Clientes (Churn) - TelecomX LATAM
🔹 1. Introducción
El objetivo principal de este análisis es entender los motivos por los cuales los clientes de TelecomX deciden cancelar sus servicios (Churn). La retención de clientes es crítica en el sector de telecomunicaciones, ya que adquirir un nuevo cliente es significativamente más costoso que mantener uno actual. A través de la ciencia de datos, buscamos identificar patrones de comportamiento que permitan a la empresa tomar acciones proactivas.
🔹 2. Limpieza y Tratamiento de Datos
Para asegurar la integridad del análisis, se realizaron transformaciones profundas en el conjunto de datos:
Traducción y Estandarización: Se renombraron las 21 columnas originales al español y se normalizaron los textos eliminando espacios en blanco (strip()) y convirtiendo todo a minúsculas para evitar duplicidad de categorías.
Corrección de Tipos de Datos:
La columna Cargo_Total se transformó de texto a numérico (float), gestionando valores nulos resultantes de clientes con 0 meses de antigüedad.
Se crearon variables derivadas como Cuentas_Diarias, dividiendo el cargo mensual por 30 para entender el impacto del gasto diario.
Codificación Binaria: Se transformaron variables de texto ("Sí"/"No") en valores numéricos (1/0). Esto permitió realizar operaciones matemáticas y correlaciones que antes eran imposibles.
Manejo de Valores Faltantes: Se identificaron y corrigieron errores de mapeo que generaban valores nulos (NaN), asegurando una base de datos 100% limpia para graficar.
🔹 3. Análisis Exploratorio de Datos (EDA)
A través de las visualizaciones generadas, se identificaron los siguientes hallazgos:
Tasa de Abandono: La proporción de evasión se sitúa cerca del 26.5%. Aunque la mayoría permanece, el grupo que se va es lo suficientemente grande como para impactar la rentabilidad.
Antigüedad Crítica: Los histogramas muestran que el riesgo de abandono es máximo en los primeros 6 meses. Si un cliente supera el primer año, la probabilidad de que se quede aumenta drásticamente.
Impacto Económico: Los clientes que cancelan el servicio tienden a tener Cargos Mensuales más altos que el promedio. Existe una "barrera de precio" donde el cliente empieza a percibir que el servicio no vale lo que paga.
Variables Categóricas: Los contratos mes a mes y los métodos de pago manuales (como el cheque electrónico) están fuertemente asociados con la evasión.
🔹 4. Conclusiones e Insights
El Contrato es el Predictor #1: Los clientes sin compromiso a largo plazo (contrato mensual) son los más propensos a irse ante cualquier inconveniente o oferta de la competencia.
Fuga Temprana: La empresa está fallando en retener a los nuevos usuarios. El "periodo de luna de miel" del servicio dura menos de un semestre para 1 de cada 4 clientes.
Servicios de Apoyo: Los clientes que cuentan con servicios adicionales como Soporte Técnico o Seguridad Online muestran una tasa de abandono significativamente menor, lo que indica que estos servicios generan "fricción positiva" para quedarse.
🔹 5. Recomendaciones Estratégicas
Migración de Contratos: Implementar campañas de marketing para incentivar el paso de contratos mensuales a contratos de 1 o 2 años mediante descuentos exclusivos.
Estrategia de Onboarding: Reforzar el servicio al cliente durante los primeros 90 días con llamadas de seguimiento o bonos de lealtad para reducir la fuga inicial.
Automatización de Pagos: Promover el uso de Pago Automático (Tarjeta de Crédito/Débito), ya que esto reduce la "decisión consciente de pagar" cada mes y baja el Churn.
Revisión de Precios en Fibra Óptica: Analizar si el costo de los planes de alta velocidad es competitivo, dado que los clientes de cargos altos son los que más se retiran.
