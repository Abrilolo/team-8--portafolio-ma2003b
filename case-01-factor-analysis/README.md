
---

```md
# LendSmart – Credit Risk Analysis

Este repositorio contiene el desarrollo completo de un caso de análisis de riesgo crediticio para **LendSmart**, una fintech dedicada a otorgar créditos personales y a pequeños negocios.  
El proyecto utiliza modelos estadísticos de clasificación para identificar, desde la etapa de solicitud, clientes con alta probabilidad de incumplimiento (default).

El contenido del proyecto se encuentra documentado principalmente en formato **PDF**, donde se presenta tanto el enfoque de negocio como el desarrollo técnico y los resultados del modelado .

---

## Estructura del repositorio

```text

├── LendSmart_Credit_Risk_Analysis__Full_Business_Case.pdf
│   └── Caso de negocio completo, contexto, hallazgos clave y recomendación final
│
├── LendSmart_Credit_Risk_Analysis.ipynb/pdf
│   └── Desarrollo técnico detallado: EDA, preprocesamiento, modelos LDA y QDA
│
└── README.md
└── Descripción general y guía del proyecto

```

---

## ¿Cómo consultar el proyecto?

1. **Comienza por el Business Case**  
   Revisa `LendSmart_Credit_Risk_Analysis__Full_Business_Case.pdf` para entender:
   - El problema de negocio.
   - El contexto del riesgo crediticio (~28% de defaults).
   - Los insights principales.
   - La recomendación final para LendSmart.

2. **Consulta el reporte técnico**  
   En `LendSmart_Credit_Risk_Analysis_Technical_Report.pdf` encontrarás:
   - Inspección y validación de datos.
   - Análisis exploratorio (EDA).
   - Preprocesamiento.
   - Modelado con **LDA** y **QDA**.
   - Evaluación con matrices de confusión y curvas ROC.

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
```

---
