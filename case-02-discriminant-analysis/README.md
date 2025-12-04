# LendSmart – Credit Risk Analysis

Este repositorio contiene el desarrollo completo de un caso de análisis de riesgo crediticio para **LendSmart**, una fintech dedicada a otorgar créditos personales y a pequeños negocios.  
El proyecto utiliza modelos estadísticos de clasificación para identificar, desde la etapa de solicitud, clientes con alta probabilidad de incumplimiento (default).

El contenido del proyecto se encuentra documentado principalmente en formato **PDF**, donde se presenta tanto el enfoque de negocio como el desarrollo técnico y los resultados del modelado .

---

## Estructura del repositorio

```text

case-02-discriminant-analysis/
├── LendSmart_Credit_Risk_Analysis.pdf
│   └── Reporte técnico completo con EDA, preprocesamiento y modelos LDA vs QDA
│
├── LendSmart_Credit_Risk_Analysis__Full_Business_Case.pdf
│   └── Caso de negocio: contexto, insights clave y recomendación final
│
└── LendSmart_Credit_Risk_Analysis.ipynb
    └── Notebook con el desarrollo en Python del análisis exploratorio,
        preprocesamiento, entrenamiento y evaluación de los modelos

```
---

## ¿Cómo consultar el proyecto?

1. Iniciar con `LendSmart_Credit_Risk_Analysis__Full_Business_Case.pdf`
   para entender el problema de negocio, el contexto del riesgo crediticio
   y la recomendación final para LendSmart.

2. Revisar `LendSmart_Credit_Risk_Analysis.pdf`
   para profundizar en el análisis técnico, los supuestos del modelado
   y la comparación entre LDA y QDA.

3. Consultar `LendSmart_Credit_Risk_Analysis.ipynb`
   para ver el desarrollo completo en Python:
   carga de datos, EDA, preprocesamiento, entrenamiento de modelos
   y evaluación con métricas y visualizaciones.

---

## Objetivo del análisis

Desarrollar un modelo estadístico que permita **clasificar clientes en riesgo de default**, con el propósito de:
- Reducir pérdidas financieras.
- Mejorar el proceso de originación de créditos.
- Mantener el crecimiento de la cartera bajo control de riesgo.

---

## Modelos utilizados

- **Linear Discriminant Analysis (LDA)**  
  Modelo seleccionado por su:
  - Alta interpretabilidad.
  - Estabilidad.
  - Mismo desempeño predictivo que QDA con menor complejidad.

- **Quadratic Discriminant Analysis (QDA)**  
  Utilizado como modelo de comparación, mostrando:
  - Mayor flexibilidad teórica.
  - Desempeño idéntico al de LDA en este caso.

Ambos modelos alcanzaron **accuracy y AUC = 1.00** en el conjunto de prueba, indicando una separación perfecta entre clases para el dataset analizado.

---

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Jupyter Notebook
- LaTeX (Overleaf)
- GitHub

---

## Conclusión general

El análisis demuestra que variables como el **historial de pago**, la **estabilidad laboral**, la **utilización de crédito** y la **razón deuda-ingreso** son determinantes clave del riesgo crediticio.  
Dado su desempeño perfecto y su facilidad de explicación, se recomienda implementar **LDA** como herramienta de apoyo en la toma de decisiones, iniciando con una fase piloto antes de su adopción total en el proceso de negocio.

---

## Autores

- Adrián Tavera Aquino – A01659113  
- Daniela Robles Estrada – A01659074  
- Elian Alejandro López de Alba – A01659582  

---

## Contexto académico

Proyecto académico desarrollado como parte de un curso de análisis estadístico y modelado predictivo aplicado a riesgo financiero.

---
