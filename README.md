# 📊 Proyecto de Análisis de Churn Telecom
## 🎯 Objetivo
Identificar los principales factores que influyen en la cancelación de clientes y desarrollar estrategias efectivas de retención basadas en análisis predictivo.

## 📋 Descripción
Este proyecto analiza el comportamiento de clientes de telecomunicaciones para predecir la probabilidad de cancelación de servicios (churn). Se implementan modelos de machine learning para identificar patrones y variables críticas que impactan en la decisión de los clientes.

## 🔧 Metodología
## 📊 Análisis Exploratorio
Limpieza y preprocesamiento de datos

Análisis de correlaciones y patrones

Encoding de variables categóricas

Balanceo de clases con SMOTE

## 🤖 Modelos Implementados
🔵 Regresión Logística (con normalización)

🟢 Random Forest (sin normalización)

Evaluación comparativa de performance

## 📈 Métricas de Evaluación
Accuracy, Precision, Recall, F1-Score

Matrices de confusión

Curvas ROC y AUC

Análisis de overfitting/underfitting

## 🚀 Resultados Principales
## 🏆 Performance de Modelos
Modelo	Accuracy	Precision	Recall	F1-Score
Regresión Logística	80.3%	65.2%	53.4%	58.7%
Random Forest	78.9%	63.9%	52.2%	57.5%
## 📊 Variables Más Influyentes
customer_tenure - Tiempo de permanencia (🔻 Retención)

account_Charges_Monthly - Gasto mensual (🔺 Riesgo)

account_Charges_Total - Gasto total (🔻 Retención)

internet_InternetService_Fiber optic - Servicio fibra (🔺 Riesgo)

account_Contract_Two year - Contrato largo (🔻 Retención)

## 💡 Insights de Negocio
## 🎯 Factores de Riesgo
Clientes con menos de 12 meses de antigüedad

Gasto mensual superior a $80

Usuarios de servicio de fibra óptica

Método de pago con cheque electrónico

## 🛡️ Factores de Protección
Antigüedad mayor a 24 meses

Contratos de largo plazo (2 años)

Pagos automáticos configurados

Múltiples servicios contratados

## 🚀 Estrategias de Retención
## 🎯 Programas Propuestos
"Primer Año Seguro" - Beneficios escalonados para clientes nuevos

Revisión de planes - Para clientes con alto gasto mensual

Incentivos por contrato - Descuentos por contratos largos

Programa de lealtad - Recompensas por antigüedad

## 🛠️ Tecnologías Utilizadas
Python 3.8+

Pandas - Manipulación de datos

Scikit-learn - Machine learning

Matplotlib/Seaborn - Visualizaciones

Imbalanced-learn - Balanceo de clases

Jupyter Notebook - Análisis interactivo
