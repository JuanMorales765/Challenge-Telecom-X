# 📊 Análisis de Evasión de Clientes en TelecomX

## 📌 Resumen
Este repositorio contiene un análisis exhaustivo de la evasión de clientes en TelecomX, identificando factores clave que influyen en el abandono de clientes y proporcionando insights accionables para mitigarlo.

## 🎯 Objetivo
Analizar e identificar los principales factores que contribuyen a la evasión de clientes en TelecomX mediante:
- Determinación de diversas causas que influyen en la decisión de los clientes
- Evaluación de factores mitigables basados en datos
- Propuesta de recomendaciones para mejorar la retención

## 🛠️ Librerías Utilizadas
- pandas
- numpy
- matplotlib
- seaborn

## 📂 Estructura del Proyecto

### 🔄 Transformación de Datos

#### 🔍 Exploración del Dataset
- Explorar columnas y verificar tipos de datos
- Revisar diccionario de datos para entender variables
- Identificar columnas más relevantes para el análisis

#### ✅ Verificación de Calidad
- Detectar valores faltantes, duplicados y errores de formato
- Identificar inconsistencias en datos categóricos
- Verificar integridad de los datos

#### � Manejo de Inconsistencias
- Aplicar correcciones necesarias
- Garantizar completitud y coherencia
- Preparar datos limpios para análisis

#### 💰 Columna de Cuentas Diarias
- Crear columna "Cuentas_Diarias"
- Calcular valores diarios a partir de facturación mensual
- Mejorar análisis temporal del comportamiento

#### ✨ Estandarización de Datos
- Transformación opcional pero recomendada
- Convertir valores textuales (ej. "Sí"/"No") a binarios (1/0)
- Renombrar columnas para mayor claridad
- Mejorar consistencia para análisis

### 📊 Carga y Análisis

#### 📈 Análisis Descriptivo
- Calcular métricas clave (media, mediana, desviación)
- Entender distribución y patrones de comportamiento

#### 📊 Distribución de Evasión
- Visualizar proporción entre clientes retenidos vs. evadidos
- Entender tasa base de evasión

#### 🗂️ Análisis por Variables Categóricas
- Explorar distribución de evasión en:
  - Género
  - Tipo de contrato
  - Método de pago
  - Otras categorías relevantes
- Identificar perfiles de alto riesgo

#### 🔢 Análisis por Variables Numéricas
- Analizar patrones de evasión en:
  - Gasto total
  - Duración de contrato
  - Otras métricas relevantes
- Identificar umbrales asociados a mayor evasión

## 💡 Hallazgos y Recomendaciones
El análisis proporciona insights para ayudar a TelecomX a:
- Entender causas principales de evasión
- Desarrollar estrategias de retención focalizadas
- Mejorar satisfacción y fidelización

