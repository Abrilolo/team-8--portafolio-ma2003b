# Customer Satisfaction Analysis – TechnoServe Solutions

Este repositorio contiene un **caso de estudio colaborativo** enfocado en analizar la satisfacción del cliente B2B de **TechnoServe Solutions** mediante **Análisis Factorial Exploratorio (AFE)**.  
El objetivo es identificar las **dimensiones latentes** que explican la experiencia del cliente y evaluar su impacto en métricas clave de negocio como satisfacción general, NPS, renovación y crecimiento.

El proyecto combina análisis estadístico riguroso con una interpretación orientada a negocio, reduciendo 23 variables de experiencia a un conjunto de factores claros, interpretables y accionables .

---

## Estructura del repositorio

```text

case-01-factor-analysis/
├── customer_satisfaction_analysis_team[8].ipynb
│   └── Notebook con el desarrollo técnico completo:
│      EDA, pruebas de adecuación (KMO y Bartlett),
│      extracción y rotación factorial (PCA vs ML,
│      Varimax vs Promax), cálculo de factor scores
│      y regresión con métricas de negocio.
│
├── customer_satisfaction_analysis_team[8].pdf
│   └── Reporte técnico del análisis factorial,
│      resultados, interpretación de factores
│      y conclusiones estadísticas.
│
├── executive_summary_team[8].pdf
│   └── Resumen ejecutivo enfocado en negocio,
│      hallazgos clave y recomendaciones estratégicas.
│
└── README.md
└── Descripción general y guía del proyecto

```

---

## ¿Cómo consultar el proyecto?

1. **Comenzar con el resumen ejecutivo**  
   Abrir `executive_summary_team[8].pdf` para obtener:
   - Contexto del problema.
   - Principales hallazgos.
   - Interpretación de los factores.
   - Recomendaciones de negocio.

2. **Revisar el reporte técnico**  
   Consultar `customer_satisfaction_analysis_team[8].pdf` para profundizar en:
   - Metodología del análisis factorial.
   - Comparación de modelos (PCA vs ML, Varimax vs Promax).
   - Selección del modelo final de 5 factores.
   - Resultados estadísticos e interpretación.

3. **Explorar el notebook**  
   Abrir `customer_satisfaction_analysis_team[8].ipynb` para ver el desarrollo completo en Python:
   - Preparación y limpieza de datos.
   - Pruebas de adecuación (KMO = 0.959, Bartlett p < 0.001).
   - Extracción y rotación factorial.
   - Cálculo de factor scores.
   - Relación entre factores y métricas de negocio mediante regresión lineal.

---

## Objetivo del análisis

Reducir la complejidad de la experiencia del cliente medida a través de múltiples indicadores, identificando **factores subyacentes** que expliquen la satisfacción y permitan:
- Priorizar acciones de mejora.
- Conectar experiencia del cliente con resultados de negocio.
- Apoyar la toma de decisiones estratégicas.

---

## Modelo final seleccionado

El modelo óptimo fue una solución de **5 factores**, utilizando:
- **Método:** Principal Components (PCA)
- **Rotación:** Varimax
- **Varianza explicada total:** ~61.6 %

Los factores identificados son:

- **F1 – Capacidad Técnica e Innovación**
- **F2 – Valor Financiero y Transparencia**
- **F3 – Relación Comercial y Gestión de Cuenta**
- **F4 – Gestión de Proyectos y Cumplimiento**
- **F5 – Soporte Operativo y Capacitación**

Estos factores muestran correlaciones positivas con satisfacción general, NPS, intención de renovación y crecimiento.

---

## Enfoque predictivo

Se utilizó una **regresión lineal** con los cinco factores para modelar la satisfacción general del cliente, obteniendo un **R² ≈ 0.60**, lo que confirma que las dimensiones identificadas explican una proporción significativa del desempeño percibido por el cliente.

---

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- factor_analyzer
- Jupyter Notebook
- LaTeX (Overleaf)
- GitHub

---

## Conclusión general

El análisis demuestra que la satisfacción del cliente B2B no depende de un solo elemento, sino de un conjunto de dimensiones interrelacionadas.  
El **desempeño técnico** y la **ejecución operativa** emergen como los principales impulsores, seguidos por la relación comercial, el valor financiero percibido y la calidad del soporte.  
Este enfoque permite transformar métricas dispersas en información estructurada y útil para la toma de decisiones estratégicas.

---

## Autores

- Adrián Tavera Aquino – A01659113  
- Daniela Robles Estrada – A01659074  
- Elian Alejandro López de Alba – A01659582  

---

## Contexto académico

Proyecto académico desarrollado como parte de un curso de análisis multivariado y aplicación de métodos estadísticos en ciencia de datos.
```

---
