# MegaMart – Customer Segmentation Analysis

Este repositorio presenta un **caso de análisis de segmentación de clientes** para **MegaMart**, una cadena minorista nacional.  
El objetivo del proyecto es identificar **grupos naturales de clientes** a partir de su comportamiento de compra y diseñar **estrategias de marketing diferenciadas** que mejoren la retención, el gasto y la efectividad de las campañas.

El análisis se realizó sobre una base de **3,000 clientes**, utilizando **métodos multivariados y aprendizaje no supervisado**, combinando un enfoque técnico riguroso con interpretación orientada al negocio .

---

## Estructura del repositorio

```text

case-01-customer-segmentation/
├── MegaMart_Customer_Segmentation_Analysis[8].pdf
│   └── Reporte completo del análisis: contexto de negocio,
│      metodología, segmentación de clientes y recomendaciones.
│
├── MegaMart_Customer_Segmentation_Analysis_Summary[8].pdf
│   └── Resumen ejecutivo enfocado en hallazgos clave
│      e impacto esperado para MegaMart.
│
└── README.md
└── Descripción general y guía del proyecto

```

---

## ¿Cómo consultar el proyecto?

1. **Iniciar con el resumen ejecutivo**  
   Abrir `MegaMart_Customer_Segmentation_Analysis_Summary[8].pdf` para entender:
   - El problema de negocio.
   - Los segmentos identificados.
   - Las recomendaciones estratégicas.

2. **Revisar el reporte completo**  
   Consultar `MegaMart_Customer_Segmentation_Analysis[8].pdf` para profundizar en:
   - Metodología de análisis multivariado.
   - Exploración de datos (EDA).
   - Elección del número óptimo de clusters.
   - Perfil detallado de cada segmento y su interpretación.

---

## Objetivo del análisis

Pasar de campañas genéricas a una **estrategia de marketing basada en datos**, identificando segmentos de clientes con comportamientos diferenciados para:
- Retener a los clientes de mayor valor.
- Reactivar a clientes en riesgo.
- Incrementar el gasto y la conversión.
- Optimizar el uso del presupuesto comercial.

---

## Metodología utilizada

- Exploración y limpieza de datos de comportamiento del cliente.
- Estandarización de variables (Z-score).
- Análisis de correlaciones para identificar variables clave.
- Clustering jerárquico (método Ward) para explorar la estructura de los datos.
- Segmentación final con **K-Means (k = 4)**.
- Validación mediante **coeficiente de silueta** y visualización con **PCA**.

---

## Segmentos identificados

El análisis identificó **cuatro segmentos principales**:

1. **Clientes de alto valor (~17.5%)**  
   Frecuencia alta, carritos grandes, gasto elevado y fuerte interacción digital.

2. **Clientes en riesgo (~31%)**  
   Baja frecuencia y gasto, alta recencia y menor compromiso con la marca.

3. **Clientes indecisos (~14%)**  
   Alta exploración digital, pero conversión limitada y gasto por debajo del potencial.

4. **Compradores constantes y prácticos (~37%)**  
   Comportamiento estable, gasto y frecuencia cercanos al promedio.

---

## Impacto esperado en el negocio

La adopción de una estrategia basada en esta segmentación permitiría:
- Reducir la fuga de clientes de alto valor en **20–25%**.
- Incrementar ventas físicas y digitales mediante campañas personalizadas.
- Aumentar tasas de apertura de correos entre **30–40%**.
- Mejorar la tasa de conversión entre **15–20%** frente a campañas genéricas.

---

## Herramientas utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Jupyter Notebook  
- GitHub  

---

## Conclusión general

El proyecto demuestra que el comportamiento del cliente en retail no es homogéneo y que una segmentación adecuada permite transformar datos históricos en **decisiones accionables de negocio**.  
La identificación clara de clientes de alto valor, clientes en riesgo y segmentos intermedios proporciona una base sólida para estrategias de marketing más eficientes y centradas en el cliente.

---

## Autores

- Adrián Tavera Aquino – A01659113  
- Daniela Robles Estrada – A01659074  
- Elian Alejandro López de Alba – A01659582  

---

## Contexto académico

Proyecto desarrollado para la materia  
**Aplicación de Métodos Multivariados en Ciencia de Datos (MA2003B)**  
Tecnológico de Monterrey


---

